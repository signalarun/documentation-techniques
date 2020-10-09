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
    markdown build
    ```
    This generates a site folder with all documentation. Serve it from your server root
  - [Tutorial](https://www.youtube.com/watch?v=aXxt9OZNhnU)
