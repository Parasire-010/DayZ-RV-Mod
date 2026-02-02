# DayZ-RV-Mod

A fully functional RV vehicle mod for DayZ with two operational modes: **Drive Mode** and **Camp Mode**.

## Overview

This mod adds a realistic RV (Recreational Vehicle) that serves as a mobile base. Players can drive it to a location and deploy it as a functional camp with powered utilities and water supply.

## Features

### Two Modes

#### Drive Mode
- Fully drivable vehicle
- Standard vehicle controls
- Compact mode for transportation
- Storage accessible but utilities disabled

#### Camp Mode
- Deployable/stationary mode
- All utilities become functional
- Interior access enabled
- Full crafting and survival functionality

### Resource System

The RV requires specific resources to power its utilities in Camp Mode:

#### Generator Rack
- External mounting point for portable generator
- Powers all electrical systems
- Generator must be fueled and running
- Required for: lights, electric stove operation

#### Water Tank
- Fillable water storage system
- Capacity: [TBD - suggest 50-100L]
- Must be filled from water sources
- Required for: sink functionality

#### Gas Canister Slot
- Attachment slot for gas canister
- Powers gas appliances
- Required for: stove/cooking functionality

### Functional Utilities

All utilities only work in **Camp Mode** when proper resources are equipped:

#### Lights
- Interior lighting system
- **Requires:** Generator (fueled and running)
- Toggle on/off in camp mode

#### Sink
- Functional water source
- **Requires:** Filled water tank
- Use for: drinking water, washing items, filling containers
- Water consumption depletes tank

#### Stove
- Cooking surface for food preparation
- **Requires:** 
  - Gas canister (for flame)
  - Generator (for electric ignition/controls)
- Standard DayZ cooking mechanics

### Storage
- Built-in storage compartments
- Accessible in both modes
- Capacity: [TBD]

### Crafting Stations
- [TBD - specify which crafting stations]
- Only functional in Camp Mode

## Planned Implementation

### Phase 1: Basic Structure
- [ ] Create RV vehicle model (or source existing asset)
- [ ] Implement basic vehicle physics and driving
- [ ] Set up drive mode functionality

### Phase 2: Mode Switching
- [ ] Implement camp mode deployment system
- [ ] Create mode toggle mechanism
- [ ] Lock vehicle movement in camp mode

### Phase 3: Resource Slots
- [ ] Add generator rack attachment point
- [ ] Implement water tank system
- [ ] Add gas canister slot
- [ ] Create UI for resource status

### Phase 4: Utilities
- [ ] Implement lighting system with generator requirement
- [ ] Add sink functionality with water tank integration
- [ ] Create stove system requiring both gas and generator
- [ ] Add resource consumption mechanics

### Phase 5: Storage & Polish
- [ ] Implement storage system
- [ ] Add crafting station integration
- [ ] Balance resource consumption rates
- [ ] Testing and bug fixes

## Technical Notes

### No 3D Modeling Experience?
Since you mentioned having no 3D modeling skills, here are some options:

1. **Use Existing Models:**
   - Look for existing RV/vehicle models in DayZ modding community
   - Adapt vanilla vehicle models
   - Use free 3D models with appropriate licenses

2. **Community Resources:**
   - DayZ Modding Discord communities
   - Bohemia Interactive forums
   - Workshop collaborations

3. **Focus on Functionality:**
   - Start with existing vehicle as base
   - Focus on scripting the unique mechanics
   - Add visual elements later through collaboration

### Required Skills/Tools
- **DayZ Tools:** Official modding toolkit from Bohemia Interactive
- **Scripting:** EnScript (DayZ's scripting language)
- **3D Software (optional):** Blender, Object Builder (for model modifications)
- **Configuration:** Understanding of DayZ config files

## Resources for Learning

- [Official DayZ Modding Documentation](https://community.bistudio.com/wiki/DayZ:Modding)
- DayZ Modding Discord servers
- Bohemia Interactive forums - Modding section
- YouTube tutorials on DayZ vehicle modding

## Contributing

Contributions are welcome! Especially:
- 3D modelers for RV assets
- Scripters familiar with DayZ vehicle systems
- Testers
- Texture artists

## License

MIT License - See LICENSE file for details

## Status

**Project Status:** Planning/Initial Development

**Looking for:**
- 3D modeler for RV vehicle asset
- Collaborators with DayZ modding experience
- Testers once basic functionality is implemented
