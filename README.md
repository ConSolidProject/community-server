# LBDserver CSS
The LBDserver Solid Community server will implement the following changes:

- Container metadata (.meta) CAN be changed via SPARQL updates. This does NOT conform to the Solid specifications but is necessary in this research to achieve a straightforward solution for metadata triples. The actual containment triples are still recreated automatically upon GET request.