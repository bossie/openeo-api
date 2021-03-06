# openEO API

openEO develops an open API to connect R, Python and JavaScript clients to big Earth observation cloud back-ends in a simple and unified way. This repository contains this API, the openEO (core) API.

* **[Latest Version of the Specification](https://api.openeo.org)**

## Versions / Branches

The [master branch](https://github.com/Open-EO/openeo-api/tree/master) is the 'stable' version of the openEO API specification. It is currently version **1.0.0-rc.2** of the specification. The [draft branch](https://github.com/Open-EO/openeo-api/tree/draft) is where active development takes place.

| Version / Branch                                          | Status      | Description |
| --------------------------------------------------------- | ----------- | ----------- |
| [draft](https://api.openeo.org/draft)                     | planned     | *Unstable* - Bug fixes based on developer feedback, introduce extension concept. Potentially version 1.0.0-final. |
| [**1.0.0-rc.2**](https://api.openeo.org)                  | **current** | Release candidate 2 for first stable version of openEO, see the [changelog](CHANGELOG.md#100-rc2---2020-02-20). |
| [1.0.0-rc.1](https://api.openeo.org/1.0.0-rc.1)           | legacy      | Release candidate 1 for first stable version of openEO, see the [changelog](CHANGELOG.md#100-rc1---2020-01-31). |
| [0.4.2](https://api.openeo.org/v/0.4.2)                   | legacy      | Bugfix release, see the [changelog](CHANGELOG.md#042---2019-06-11). |
| [0.4.1](https://api.openeo.org/v/0.4.1)                   | legacy      | Bugfix release, see the [changelog](CHANGELOG.md#041---2019-05-29). |
| [0.4.0](https://api.openeo.org/v/0.4.0)                   | legacy      | Improved discovery, added processes catalogue, new process graph structure and [more](CHANGELOG.md#040---2019-03-07). |
| [0.3.1](https://api.openeo.org/v/0.3.1)                   | legacy      | Fixing minor issues, see the [changelog](CHANGELOG.md#031---2018-11-06). |
| [0.3.0](https://api.openeo.org/v/0.3.0)                   | legacy      | Major rework. |
| [0.0.2](https://github.com/Open-EO/openeo-api/tree/0.0.2) | legacy      | Proof of concept, implemented. |
| [0.0.1](https://github.com/Open-EO/openeo-api/tree/0.0.1) | legacy      | First draft with basic ideas, loosely implemented. |

See also the [changelog](CHANGELOG.md) and the [milestones](https://github.com/Open-EO/openeo-api/milestones) for a rough roadmap based on GitHub issues.

## Repository

This repository contains a set of files formally describing the openEO API, each with a human-readable and easily browseable version:

* [openapi.yaml](openapi.yaml) provides the [OpenAPI](https://www.openapis.org/) 3.0 definition of the openEO API. See the table above for human-readable versions of the OpenAPI definition.
* [errors.json](errors.json) is a list of potential global error codes and messages, excluding specific exceptions separately available for each process.
* [subtype-schema.json](subtype-schema.json) defines data types (subtypes) for JSON Schema used in openEO.
* The [assets](assets/) folder contains some useful additional files such as examples or schemas. All of these are non-binding additions. The source of truth are the top-level specification files.
