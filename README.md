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

## India Owners

[Fill in description] [what is edge value?]

- "nodeid" variable in nodelist are the node IDs connected with the "sender" and "recver" columns in the edgelist.

## Hassan Dissertation Data

[No data]

## Fire Chasers

Collaborations between people fighting fires in the forest. Contains information about coordination, and the effectiveness of fire fighting.

- "MergeParticipantID" variable in nodelist are the node IDs connected with the "MergeParticipantID" and "Target_MergeParticpantID" columns in the edgelist.

- The "forest" variable in the nodelist and the "RespondentForestID" and "Target_ForestID" in the edgelist indicate which forest the firemen are working and interacting in.

## Daly Leaders

Collaboration between school administrators in two school districts. Different types of relationships to analyze, in addition to information about their perceived trust and effectiveness.

- "numid" variable in nodelist are the node IDs connected with the "numid1" and "numid2" columns in the edgelist.

- The "District_Site" variable in the nodelist indicates which district the staff is working in.

## Capital Partners

Collaborations between agents at three commercial real estate firms. Contains different types of relationships, like support, advice and socializing. Good for generating questions about network overlap.

- "numid" variable in nodelist are the node IDs connected with the "numid1" and "numid2" columns in the edgelist.

- "Capital_Partners_case.pdf" has information about the organization, and the direction of the study.

- "Capital_Partners_Survey.pdf" contains the survey information and codebook.


