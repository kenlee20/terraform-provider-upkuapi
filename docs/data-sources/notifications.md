---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "kuma_notifications Data Source - kuma"
subcategory: ""
description: |-
  
---

# kuma_notifications (Data Source)



## Example Usage

```terraform
# List all of notifications
data "kuma_notifications" "all" {}
```

<!-- schema generated by tfplugindocs -->
## Schema

### Read-Only

- `notifications` (Attributes List) (see [below for nested schema](#nestedatt--notifications))

<a id="nestedatt--notifications"></a>
### Nested Schema for `notifications`

Read-Only:

- `active` (Boolean)
- `default` (Boolean)
- `id` (Number)
- `name` (String)
- `type` (String)
- `user_id` (Number)
