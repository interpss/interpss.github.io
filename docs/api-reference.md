---
layout: default
title: API Reference
nav_order: 5
---

# API Reference

The InterPSS API documentation provides comprehensive coverage of all classes, interfaces, and methods available in the InterPSS library.

## Online API Documentation

**[📖 Browse Complete API Documentation](../api_doc/index.html){: .btn .btn-primary .fs-5 .mb-4 .mb-md-0 .mr-2 target="_blank"}**

## Quick Links

### Core Modules

| Module | Description | Documentation |
|--------|-------------|---------------|
| **Core** | Core power system analysis functionality | [com.interpss.core](../api_doc/com/interpss/core/package-summary.html) |
| **ACLF** | AC Load Flow analysis | [com.interpss.core.aclf](../api_doc/com/interpss/core/aclf/package-summary.html) |
| **Dynamic Stability** | Transient stability analysis | [com.interpss.dstab](../api_doc/com/interpss/dstab/package-summary.html) |
| **DC Analysis** | DC load flow and sensitivity | [com.interpss.dc](../api_doc/api_doc/com/interpss/dc/package-summary.html) |
| **Optimal Power Flow** | OPF algorithms | [com.interpss.opf](../api_doc/api_doc/com/interpss/opf/package-summary.html) |

### Key Factory Classes

- **[CoreObjectFactory](../api_doc/com/interpss/core/CoreObjectFactory.html)** - Main factory for creating core objects
- **[DclfAlgoObjectFactory](../api_doc/com/interpss/core/DclfAlgoObjectFactory.html)** - DC load flow algorithm factory
- **[DstabFactory](../api_doc/com/interpss/dstab/DstabFactory.html)** - Dynamic stability object factory

### Network Models

- **[AclfNetwork](../api_doc/com/interpss/core/aclf/AclfNetwork.html)** - AC load flow network model
- **[DStabilityNetwork](../api_doc/com/interpss/dstab/DStabilityNetwork.html)** - Dynamic stability network model
- **[AclfBus](../api_doc/com/interpss/core/aclf/AclfBus.html)** - AC load flow bus model
- **[AclfBranch](../api_doc/com/interpss/core/aclf/AclfBranch.html)** - AC load flow branch model

### Algorithm Classes

- **[LoadflowAlgorithm](../api_doc/com/interpss/core/algo/LoadflowAlgorithm.html)** - Load flow solver
- **[SenAnalysisAlgorithm](../api_doc/com/interpss/core/algo/dclf/SenAnalysisAlgorithm.html)** - Sensitivity analysis (LODF, GSF)
- **[ContingencyAnalysisAlgorithm](../api_doc/com/interpss/core/algo/ContingencyAnalysisAlgorithm.html)** - Contingency analysis

## Documentation Usage

The API documentation is generated using Javadoc and includes:

- **Class hierarchies** and inheritance relationships
- **Method signatures** with parameter types and return values  
- **Code examples** and usage patterns
- **Cross-references** between related classes
- **Search functionality** for finding specific classes or methods

## Getting Started

1. **Browse by package** using the [package list](../api_doc/overview-frame.html)
2. **Search for classes** using the [alphabetical index](../api_doc/allclasses-frame.html) 
3. **Find specific methods** using the search functionality
4. **Follow inheritance chains** using the class hierarchy trees

---

*Last updated: August 2025*
