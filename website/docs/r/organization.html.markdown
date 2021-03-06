---
layout: "packet"
page_title: "Packet: packet_organization"
sidebar_current: "docs-packet-resource-organization"
description: |-
  Provides a Packet Organization resource.
---

# packet\_organization

Provides a resource to manage organization resource in Packet.

## Example Usage

```hcl
# Create a new Project
resource "packet_organization" "tf_organization_1" {
  name        = "foobar"
  description = "quux"
}
```

## Argument Reference

The following arguments are supported:

* `name` - (Required) The name of the Organization
* `description` - Description string
* `website` - Website link
* `twitter` - Twitter handle
* `logo` - Logo URL


## Attributes Reference

The following attributes are exported:

* `id` - The unique ID of the organization
* `name` - The name of the Organization
* `description` - Description string
* `website` - Website link
* `twitter` - Twitter handle
* `logo` - Logo URL
