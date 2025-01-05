# nets_management_2025
 Data and descriptions for Networks and Management - Spring 2025

## Neogen

Relationships between employees in an organization. Check "Lex Codebook and Scale Attribute Dataset.doc" for more information about the variables. Contains several different types of relationships.

- "unodes" variable in the nodelist are the node IDs connected to the "From" and "To" columns in the edgelist.

- The variable "Building" and "Buildingc" represent the different building that employees work in.

- "neo_edges" contains all the relationships, while "neo_edges_a", "neo_edges_r", "neo_edges_c", "neo_edges_f" contain specific relationships.

- To open all the raw data, use the load("path") and replace path with the location of "neogen.RData"

- "nodes.csv" and "edges.csv" are the complete nodes and edges.

## Milltown

Relationships between teachers and staff inside a school. The codebook containing questions and variable name is "Teacher Survey Blind.pdf". Background information about the school, setting and historical context is available in "mill town case.pdf"

- "id" variable in nodelist are the node IDs connected with the "ego" and "alter" columns in the edgelist.

- The "compleated_network" variable in the nodelist tells us if the respondent compleated the full network section. Careful, they are still included in the edgelist! But their responses might be partial.

- "mill_edges" contains all the relationships, while "mill_edges_c", "mill_edges_r", "mill_edges_p" contain specific relationships.

## India Owners

Co-Ownership network among Indian firms. Edge values are co-ownership levels. For more information, read:

Mani, Dalhia  and James Moody “Moving beyond stylized economic network models The Hybrid World of the Indian Firm Ownership Network”  American Journal of sociology 119:1629-1669

- "nodeid" variable in nodelist are the node IDs connected with the "sender" and "recver" columns in the edgelist.

- "information" document contains information about the creation of the network.

## Hassan Dissertation Data

Inter-organizational relationships between employees. Contains information about which employee exited or got promoted, and multiple organizations to compare. You can also read the dissertation that was based on this data for some ideas!

- "id" variable in nodelist are the node IDs connected with the "from" and "to" columns in the edgelists.

- edgelists are split into different organizations, numbered from 1 to 6.

- In the nodelist, the "exit" and "promotion" columns indicate the outcome for each employee.

## Fire Chasers

Collaborations between people fighting fires in the forest. Contains information about coordination, and the effectiveness of fire fighting.

- "MergeParticipantID" variable in nodelist are the node IDs connected with the "MergeParticipantID" and "Target_MergeParticpantID" columns in the edgelist.

- The "forest" variable in the nodelist and the "RespondentForestID" and "Target_ForestID" in the edgelist indicate which forest the firemen are working and interacting in.

## Daly Leaders

Collaboration between school administrators in two school districts. Different types of relationships to analyze, in addition to information about their perceived trust and effectiveness.

- "numid" variable in nodelist are the node IDs connected with the "numid1" and "numid2" columns in the edgelist.

- The "District_Site" variable in the nodelist indicates which district the staff is working in.

- The data is split into two samples. "daly_nodes" and "daly_edges" contains both, while "daly_nodes_1", "daly_edges_1", "daly_nodes_2" and "daly_edges_2" contains individuals samples.

## Capital Partners

Collaborations between agents at three commercial real estate firms. Contains different types of relationships, like support, advice and socializing. Good for generating questions about network overlap.

- "numid" variable in nodelist are the node IDs connected with the "numid1" and "numid2" columns in the edgelist.

- "Capital_Partners_case.pdf" has information about the organization, and the direction of the study.

- "Capital_Partners_Survey.pdf" contains the survey information and codebook.

- "cp_edges" contains all the relationships, while "cp_edges_w", "cp_edges_p", "cp_edges_s", "cp_edges_a" contain specific relationships.


