# tunnel-explorer-pipeline
A compilation package for the visualisation and mechanistic analysis of protein tunnels.

Background 

Exploration of the protein channel and tunnels provides invaluable informations for subsrtate binding pathways, therefore the catalysis mechanisms of enzymes. Protein tunnels are
composed of varying aminoacid and cofactors, giving distinctive profiles. Powerful channel exploration tools exist in the literature. A command line tool, CAVER
(https://caver.cz/) written with java is widely used to analyze tunnel/channel ın protein crystal structures. CAVER uses Voronoi diagramms to define possible pathways to the
selected cavities. Proposed pathways have to be post-processed according to the aligining residues to be identified as as tunnels. 

A proper pipeline will be needed to be able to integrate the channel calculation with the post-processing. Additionaly, comparisions between different crystal structures obtained
in different conditions such as buffer types, pH, beamline power or site-specifi muattions can be easily made by building up a database.           

Brief Description of the project

To achieve mentioned purposes, a java kernel implementation is needed (such as https://github.com/n-riesco/ijavascript) to be able to run java-based CAVER algorithm.
The post-processing of calculated pathways will then be analyzed using the self written modules. Additionally, a pymol interpeter (https://github.com/orkunaydin/3Dmo$ will be used
in Jupyter notebook to create figures and visualisations. 
