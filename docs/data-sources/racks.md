---
# generated by https://github.com/fbreckle/terraform-plugin-docs
page_title: "netbox_racks Data Source - terraform-provider-netbox"
subcategory: "Data Center Inventory Management (DCIM)"
description: |-
  
---

# netbox_racks (Data Source)





<!-- schema generated by tfplugindocs -->
## Schema

### Optional

- `filter` (Block Set) (see [below for nested schema](#nestedblock--filter))
- `limit` (Number) Defaults to `0`.

### Read-Only

- `id` (String) The ID of this resource.
- `racks` (List of Object) (see [below for nested schema](#nestedatt--racks))

<a id="nestedblock--filter"></a>
### Nested Schema for `filter`

Required:

- `name` (String)
- `value` (String)


<a id="nestedatt--racks"></a>
### Nested Schema for `racks`

Read-Only:

- `asset_tag` (String)
- `comments` (String)
- `custom_fields` (Map of String)
- `desc_units` (Boolean)
- `description` (String)
- `facility_id` (String)
- `id` (Number)
- `location_id` (Number)
- `max_weight` (Number)
- `mounting_depth` (Number)
- `name` (String)
- `outer_depth` (Number)
- `outer_unit` (String)
- `outer_width` (Number)
- `role_id` (Number)
- `serial` (String)
- `site_id` (Number)
- `status` (String)
- `tags` (Set of String)
- `tenant_id` (Number)
- `type` (String)
- `u_height` (Number)
- `weight` (Number)
- `weight_unit` (String)
- `width` (Number)

