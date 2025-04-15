# SchemaX

SchemaX is a community curated collection of extended JSON schemas available on the internet. This repository aims to be a comprehensive resource for developers looking for specialized or enhanced JSON schema definitions across various domains.

## Overview

JSON Schema is a powerful tool for validating the structure of JSON data. Extended JSON schemas build upon the standard specification to provide domain-specific validation rules, additional keywords, and enhanced functionality.

This collection focuses on schemas that extend the core JSON Schema specification with additional features, vocabularies, or domain-specific validations.

## Contributing

We welcome contributions to SchemaX! If you know of extended JSON schemas that should be included in this collection, please submit a pull request with:

1. The schema name and link
2. A brief description
3. Any relevant documentation links
4. Tags/categories for the schema

### Filename Convention

When submitting schema extensions, please follow these filename conventions:

- For extending existing standards, use the format: `{base-standard}.v{base-version}-{extension-name}.v{extension-version}.json`
  - Example: `oas.v3.0-redoc.v2.0.json` for Redoc v2.0 extensions to OAS 3.0
  - Example: `jsonschema.v2019-09-validation.v1.0.json` for custom validation extensions v1.0 to JSON Schema 2019-09

- For domain-specific schemas, use: `{domain}-{purpose}.v{version}.json`
  - Example: `ecommerce-product.v1.0.json` for an e-commerce product schema v1.0

This way, both the base schema version and the extension version are clearly indicated, eliminating any ambiguity. The "v" prefix before version numbers makes it even clearer which part is the version identifier.

## Usage

Each schema in the collection includes links to the original source and documentation. To use a schema, follow the specific instructions provided by its maintainers.

## License

This collection is licensed under MIT. Individual schemas may have their own licenses - please refer to the original schema documentation for details.

## Acknowledgments

Thanks to all the schema authors and maintainers who make their work available to the community.

---

**Note:** This README provides links to external schemas maintained by their respective owners. SchemaX does not host the schemas directly but serves as a reference collection.
