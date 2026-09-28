# DocHub

Public, version-controlled policy and support pages for independent applications.

## Published routes

- [`/products/keyact/`](products/keyact/) — KeyAct document index
- [`/products/keyact/privacy/`](products/keyact/privacy/) — KeyAct privacy policy
- [`/products/keyact/support/`](products/keyact/support/) — KeyAct support
- [`/products/ping-light/`](products/ping-light/) — Ping Light document index
- [`/products/ping-light/privacy/`](products/ping-light/privacy/) — Ping Light privacy policy
- [`/products/ping-light/support/`](products/ping-light/support/) — Ping Light support

## Product document convention

Create a self-contained product directory under `products/<product-slug>/`:

```text
products/
  <product-slug>/
    index.html        # public product-document index
    privacy/index.html
    support/index.html
    terms/index.html  # add only where the product actually has terms
    eula/index.html   # add only when a custom EULA is used
    licenses/index.html
```

Keep each document product-specific, link it from both its product index and the root index, and preserve existing URLs when updating an established document. Use only public contact information. Do not commit credentials, customer data, support tickets, analytics exports, or unpublished release material.
