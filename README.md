# Documentation Techniques
 ## Mkdocs-material
  - Allows to create documentaion using markdowns
  - pip install mkdocs-material
  - Generate site folder by
    ```
    mkdocs new .
    ```
  - Add below to mkdocs.yml  
  
    ```
     theme:
       name: material
     ```
  - Add markdows to generated docs folder   
  - mkdocs serve --dev-addr=0.0.0.0:80
  - For serving from your own server
    ```
    mkdocs build
    ```
    This generates a site folder with all documentation. Serve it from your server root.
  - [Tutorial](https://www.youtube.com/watch?v=aXxt9OZNhnU)

## https://www.doxygen.nl/index.html
  
## Converting markdowns to html
  + [Pandoc](https://pandoc.org/)
    - Pandoc is a free and open-source document converter. Its a swis army knife in document conversion.
    - sudo apt-get install pandoc
  
## Youtube links to markdown
  1. https://video-to-markdown.netlify.app/
