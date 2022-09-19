# Terraform Child Module Template

Adjust this readme as part of your first commit after creating a repository from this template.

[See here](https://github.com/terraform-docs/terraform-docs) for more information about the Terraform docs generator.

<!-- BEGIN_TF_DOCS -->
{{ .Content }}
<!-- END_TF_DOCS -->

Run this when you create a repo: 

```sh
echo '/usr/local/bin/terraform-docs md --output-file README.md .' >> .git/hooks/pre-commit && chmod a+x .git/hooks/pre-commit
```

Then delete this message.
