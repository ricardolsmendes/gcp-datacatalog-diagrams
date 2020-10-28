# How to Contribute

We'd love to accept your patches and contributions to this project.
There are just a few small guidelines you need to follow.

## Always update the PNG files
 
Before submitting a PR, please make sure all PNG images are up-to-date.
The PlantUML CLI helps to get the job done, as follows:

1. Download the latest version of `plantuml.jar`
   (https://sourceforge.net/projects/plantuml/files/plantuml.jar/download)

1. Use the CLI to generate diagrams:
   ```shell script
   java -jar <PLANTUML-JAR-FOLDER>/plantuml.jar \
     -checkmetadata \
     ./mental-model/*plantuml
   ```
   
Check [PlantUML CLI docs](https://plantuml.com/command-line) for additional options.
