---
version: '2.0'
license: community
---

# ID

The `id` field is used to show the record's id. By default it's visible only on the `Index` and `Show` views. This is a good field to add `as_link_to_resource` option to make it a shortcut to the record `Show` page.

```ruby
field :id, as: :id
```

## Options

<!-- @include: ./../common/link_to_resource_common.md-->
