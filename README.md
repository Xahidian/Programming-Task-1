# Programming Task 1

## Graph Search Algorithm
### Course: IT00CD89-3005 Graph Algorithms 

-------
**Submitted By:**
**MD Hasibul Haque Zahid (2302302)** 

-------

### Implementation

This Python script processes graph data from a CSV file and generates two different representations: an adjacency matrix and a tabular format. The script supports both directed and undirected graphs.

-------
### Application Working Process

- Reading Graph Data: The read_graph_data function reads the graph data from a CSV file. Each row in the file represents an edge in the graph and should contain four fields: two vertices, a weight, and an edge ID.
- Getting Vertices: The get_vertices function extracts all unique vertices from the list of edges.
- Creating Adjacency Matrix: The create_adjacency_matrix function creates an adjacency matrix representation of the graph.
- Creating Tabular Format: The create_tabular_format function creates a tabular format representation of the graph.
- Writing to File: The write_matrix_to_file and write_tabular_format_to_file functions write the adjacency matrix and tabular format to CSV files, respectively.
- Main Function: The main function orchestrates the entire process. It reads the graph data, generates the vertices list, asks the user whether the graph is directed or not, creates the adjacency matrix and tabular format, and writes them to files.

-------
### Troubleshooting
If we encountered any issues while testing the code, we checked the following:

1. Made sure that the CSV file was in the correct format and that the file path was correct.
2. Ensured that we had the necessary Python libraries installed.

-------
### Testing Process

- Prepare Test Data: Create a CSV file with your test graph data. Each row should represent an edge and contain four fields: two vertices, a weight, and an edge ID.
- Run the Script: Run the script and provide the path to your test graph data file when prompted.
- Specify Graph Type: When asked whether the graph is directed, enter ‘y’ for a directed graph and ‘n’ for an undirected graph.
- Check the Output: The script will create two output files: ‘directed_adjacency_matrix.csv’ and ‘directed_tabular_format.csv’ for a directed graph, or ‘undirected_adjacency_matrix.csv’ and ‘undirected_tabular_format.csv’ for an undirected graph. Open these files and  verify that the adjacency matrix and tabular format match your expectations based on the input graph data.
