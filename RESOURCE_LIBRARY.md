# Resource Library Registration

This document explains the metadata files added to register this repository in the Aurelius Federal Platform Resource Library.

## Overview

The SkillTree Service has been cataloged in the Aurelius Federal Platform Resource Library through the addition of three standardized metadata files. These files enable automated discovery, cataloging, and integration with federal resource management systems.

## Metadata Files

### 1. codemeta.json

**Purpose**: Provides machine-readable software metadata following the [CodeMeta 3.0 specification](https://codemeta.github.io/)

**Key Information Included**:
- Software identification (name, version, identifier)
- Programming languages and frameworks
- Runtime platform requirements
- License information (Apache 2.0)
- Repository and documentation links
- Author and maintainer information
- Keywords for discovery
- Build and deployment requirements

**Used By**: Software catalogs, dependency management systems, research databases

### 2. CITATION.cff

**Purpose**: Provides citation information in [Citation File Format](https://citation-file-format.github.io/)

**Key Information Included**:
- Proper citation format for academic/research use
- Software title and abstract
- Author information
- Repository URL and license
- Version and release date
- Keywords and programming languages

**Used By**: Research papers, academic citations, GitHub citation feature, DOI minting systems

### 3. resource-library.json

**Purpose**: Provides Aurelius Federal Platform-specific catalog metadata

**Key Information Included**:
- Platform: Aurelius Federal Platform
- Resource classification (Education & Training, Learning Management System)
- Technical architecture details
- Deployment options and requirements
- Security and compliance information
- Feature list and use cases
- Integration capabilities
- Support resources

**Used By**: Aurelius Federal Platform resource catalog, internal discovery systems

## How These Files Are Used

### For Resource Discovery
- The metadata files enable automated scanning and indexing by federal resource catalogs
- Keywords and classification help users find this software when searching for training and gamification platforms
- Technical details help system administrators assess compatibility with their infrastructure

### For Integration
- The files provide all necessary information for integrating this software into federal IT ecosystems
- Security and compliance information helps with authorization processes
- Deployment details assist with planning and implementation

### For Maintenance
- Version information enables tracking of software updates
- Author and maintainer information provides points of contact
- Support resources direct users to appropriate help channels

## Updating Metadata

When updating the repository, please ensure these metadata files are kept current:

1. **Version Changes**: Update the `version` field in all three files when releasing new versions
2. **Feature Updates**: Update the features list in `resource-library.json` when adding significant new capabilities
3. **Dependency Changes**: Update technical details when changing major frameworks or runtime requirements
4. **Contact Changes**: Update maintainer information if organizational changes occur

## Validation

All metadata files have been validated for proper syntax:
- JSON files (`codemeta.json`, `resource-library.json`): Valid JSON format
- YAML file (`CITATION.cff`): Valid YAML format conforming to CFF 1.2.0 specification

## Additional Resources

- [CodeMeta Project](https://codemeta.github.io/)
- [Citation File Format](https://citation-file-format.github.io/)
- [SkillTree Official Documentation](https://code.nsa.gov/skills-docs/)
- [Repository](https://github.com/AureliustechandTalentSolutions/skills-service)

## Support

For questions about resource library registration or metadata:
- File an issue on the [GitHub repository](https://github.com/AureliustechandTalentSolutions/skills-service/issues)
- Contact: Aurelius Tech and Talent Solutions
