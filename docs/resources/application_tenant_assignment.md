---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "frontegg_application_tenant_assignment Resource - terraform-provider-frontegg"
subcategory: ""
description: |-
  Configures a Frontegg application tenant assignment.
---

# frontegg_application_tenant_assignment (Resource)

Configures a Frontegg application tenant assignment.

## Example Usage

```terraform
resource "frontegg_application_tenant_assignment" "example" {
  app_id    = "app-1234567890"
  tenant_id = "tenant-1234567890"
}
```

<!-- schema generated by tfplugindocs -->
## Schema

### Required

- `app_id` (String) The ID of the application.
- `tenant_id` (String) The ID of the tenant.

### Read-Only

- `id` (String) The ID of this resource.
