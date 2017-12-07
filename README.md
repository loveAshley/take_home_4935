# take_home_4935

# Create a new to-do item:
Request Method: POST
Path: /create/{title}
Sample URL: http://{hostname}:3000/create/run

# Read all to-do item:
Request Method: GET
Path: /read
Sample URL: http://{hostname}:3000/read

# Update a new to-do item to completed status:
Request Method: POST
Path: /update/{title}
Sample URL: http://{hostname}:3000/update/run

# Delete a completed to-do item:
Request Method: DELETE
Path: /delete/{title}
Sample URL: http://{hostname}:3000/delete/run

# Search for a to-do item
Request Method: GET
Path: /query
Sample URL: http://{hostname}:3000/query?title=run
            http://{hostname}:3000/query?status=NEW
            http://{hostname}:3000/query?title=run&status=NEW
