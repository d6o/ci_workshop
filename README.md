# ci_workshop

https://docs.google.com/presentation/d/1IJWDDepnUJaX977XTRIyoWNTrfoWlKj-J6Z1iiLU7sQ/edit?usp=sharing

# web interface
http://144.202.13.225:8080/

# login
user: test
pass: test
 
# Login from cli
fly -t tutorial login -c http://144.202.13.225:8080 -u test -p test

# Set pipeline
fly -t tutorial set-pipeline -p "test" -c pipeline.yaml

# Destroy pipeline
fly -t tutorial destroy-pipeline -p "test"
