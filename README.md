# Insight DevOps Engineering Systems Puzzle


# Mainly worked on following files:

- docker-compose.yml


                Removed the Networks as i felt we didn't need multi hosts in a simple problem like this.
                
                Ensured depends_on is correct for both flaskapp and nginx.
                
                Provided ports for flaskapp too.
                
                Ensured volumes are mapped properly.
- Dockerfile
    
                Ensured port 5000 is also exposed.
                
                
- app.py
            
                In success method ensured data is returned and rendered 
                viewAll template (new template created) 
                

-template folder
      
      
                Added viewAll.html template
