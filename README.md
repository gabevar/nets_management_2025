# nets_management_2025
 Data and descriptions for Networks and Management - Spring 2025

## Neogen

Relationships between employees in an organization. Check "Lex Codebook and Scale Attribute Dataset.doc" for more information about the variables.

- "unodes" variable in the nodelist are the node IDs connected to the "From" and "To" columns in the edgelist.

- The variable "Building" and "Buildingc" represent the different building that employees work in.

- To open all the raw data, use the load("path") and replace path with the location of "neogen.RData"

- "nodes.csv" and "edges.csv" are the complete nodes and edges.

## Milltown

Relationships between teachers and staff inside a school. The codebook containing questions and variable name is "Teacher Survey Blind.pdf". Background information about the school, setting and historical context is available in "mill town case.pdf"

- "id" variable in nodelist are the node IDs connected with the "ego" and "alter" columns in the edgelist.

- The "compleated_network" variable in the nodelist tells us if the respondent compleated the full network section. Careful, they are still included in the edgelist! But their responses might be partial.

