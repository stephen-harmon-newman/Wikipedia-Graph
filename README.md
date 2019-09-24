# Wikipedia-Graph
A program to map Wikipedia and manipulate the map. Written by Stephen Newman.
All software is provided and licensed under the GNU GPL v3. All software is provided as is -- no guarantees are made as to its effects or functions. Any effects of the software, intentional or otherwise, are the sole responsibility of the user.

To compile a map, the program needs a Wikipedia XML dump file.

Commands:

To build the graph:
wikigraph build "xml_dump_path" (-o "output_path")

To see some general statistics on a built graph (this will be fleshed out): 
wikigraph stats (-table "tablepath")

To see info regarding an individual page:
wikigraph stats "pagename" (-table "tablepath")

To find a shortest path between two pages:
wikigraph path "firstpage" "secondpage" (-table "tablepath")

To get a random page and its links:
wikigraph random (-table "tablepath")


Tempnote: As of September 24, 2019, the current version of the program is not working. Older versions are more likely to work, but are slow. Will update when this is fixed.
