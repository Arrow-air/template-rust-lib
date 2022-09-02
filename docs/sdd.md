# \<LIBRARY NAME\> - Software Design Document (SDD)

<center>

<img src="https://github.com/Arrow-air/tf-github/raw/main/src/templates/doc-banner-services.png" style="height:250px" />

</center>

## Overview

This document details the software implementation of FIXME.

This library is responsible for FIXME

Attribute | Description
--- | ---
Status | Draft

## Related Documents

Document | Description
--- | ---
FIXME | FIXME

## Module Attributes

Attribute | Applies | Explanation
--- | --- | ---
Safety Critical | ? | 
Realtime | ? |

## Global Variables

**Statically Allocated Queues**

FIXME

## Interfaces

For a refresher of the processes in the Arrow backend, please see the [top level README.md](../README.md).

```mermaid
graph LR
    subgraph Vehicle Domain
        air((Aircraft))
    end

    subgraph Client Domain
        app(App X)
    end

    subgraph Server Domain
        module[Module A]
    end
```

FIXME description of the graph.

## Tests

FIXME

### Unit Tests

FIXME
