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
                

- template folder
      
      
                Added viewAll.html template
                
     
- Following urls were handy while solving the problem:

                https://github.com/10up/wp-local-docker/issues/58
                https://stackoverflow.com/questions/48091744/error-volumes-dbdata-must-be-a-mapping-or-null
                http://flask.pocoo.org/docs/1.0/patterns/sqlalchemy/
                https://hackernoon.com/top-10-docker-commands-you-cant-live-without-54fb6377f481
                https://docs.docker.com/compose/networking/#links
                http://containertutorials.com/docker-compose/flask-compose.html
                
                
                
                
