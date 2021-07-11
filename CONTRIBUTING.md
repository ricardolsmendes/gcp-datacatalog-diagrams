# How to Contribute

We'd love to accept your patches and contributions to this project.
There are just a few small guidelines you need to follow.

## Code reviews

All submissions, including submissions by project members, require review. We
use GitHub pull requests for this purpose. Consult
[GitHub Help](https://help.github.com/articles/about-pull-requests/) for more
information on using pull requests.

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
