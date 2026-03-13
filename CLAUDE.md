# civil3d-scripts - Context for agent-designer

## Role
Civil 3D 2026 scripts: alignments, profiles, corridors, Dynamo automation.

## Structure
- scripts/alignments/ - alignment scripts
- scripts/profiles/ - EG/FG profile generation
- scripts/corridors/ - corridor assemblies, daylight
- dynamo/graphs/ - Dynamo .dyn files (DesignScript)

## Rules
- Use ezdxf for DWG reading outside Civil 3D
- Dynamo: DesignScript only, no Python nodes
- Test against sample data in examples folder

## Normatives
- SP 34, SP 396
