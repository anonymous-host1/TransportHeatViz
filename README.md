# Transportation Users Heat Impacts and Adaptation Strategies - Interactive Visualization

## Description

This interactive visualization platform maps the global distribution of heat-related impacts on transportation systems and their corresponding adaptation strategies. Developed as part of a comprehensive study on extreme heat impacts on transportation, this tool provides a geospatial complement to traditional tabular evidence synthesis.

The visualization employs a dynamic mapping interface that enables users to explore heat-related transportation challenges and solutions across different geographical contexts, climate zones, and transportation modes. It serves both academic researchers and transportation practitioners by facilitating evidence-based climate resilience planning.

## Key Features
1. **Dual-layer visualization**: Toggle between heat impacts and adaptation strategies to see both vulnerabilities and implemented solutions
2. **Climate zone highlighting**: When selecting a location, all areas with the same Köppen climate classification are highlighted, enabling users to identify transferable strategies between climatically similar regions
3. **Dynamic clustering**: Markers adjust based on zoom level, revealing both broad regional patterns and specific local conditions
4. **Transportation mode filtering**: Filter data by specific modes (Walking, Cycling, Buses, Metro/trains, Driving)
5. **Detailed information access**: Each marker provides specific impact descriptions or adaptation strategy details, including source citations
6. **Color-coded intensity**: Markers range from cyan (fewer instances) to red (numerous instances) to indicate concentration of documented impacts or adaptations

## Applications

This visualization tool supports:

1. **Cross-regional knowledge transfer**: Identifying relevant adaptation strategies from climatically similar contexts
2. **Mode-specific vulnerability assessment**: Targeted resilience planning for specific transportation subsystems
3. **Evidence-based adaptation planning**: Direct access to documented impacts and adaptations with source citations
4. **Climate pattern analysis**: Understanding how transportation vulnerabilities manifest across different climate types

## Technical Implementation

Built using Leaflet.js, the platform features responsive design and interactive elements including dynamic filtering, climate zone highlighting, and detailed information popups. The visualization processes global data on transportation heat impacts from systematic literature review and categorizes them according to Köppen climate classifications to enable climate-sensitive analysis.

## Related Publication

This visualization accompanies the paper - Anonymous Authors _Commuting in the heat: A comprehensive review of extreme temperature impacts on transport users, behavioral adaptations and mitigation strategies._ Manuscript submitted for publication in _Sustainable Cities and Society_. This paper presents a comprehensive analysis of extreme heat impacts on transportation systems and effective adaptation strategies. The visualization helps addressing the paper's central research questions by revealing various heat vulnerability and adaptive responses worldwide.

## How to Use
1. Open the HTML file in any modern web browser
2. Use the toggle in the top right to switch between "Impacts" and "Adaptations" views
3. Click on any colored marker to view detailed information
4. When a marker is selected, all areas with the same climate classification will be highlighted
5. Use the dropdown menu to filter by transportation mode

## Requirements
1. Any modern web browser with JavaScript enabled
2. No installation required
3. Works offline after initial download

## Version

1.0.0 (Initial release)
