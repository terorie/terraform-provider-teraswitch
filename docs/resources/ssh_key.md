---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "teraswitch_ssh_key Resource - terraform-provider-teraswitch"
subcategory: ""
description: |-
  Creates and manages SSH keys for TeraSwitch servers.
---

# teraswitch_ssh_key (Resource)

Creates and manages SSH keys for TeraSwitch servers.



<!-- schema generated by tfplugindocs -->
## Schema

### Required

- `display_name` (String)
- `ssh_key` (String) The OpenSSH format SSH public key

### Read-Only

- `id` (Number) The ID of the SSH key
- `project_id` (Number) The ID of the project the SSH key belongs to