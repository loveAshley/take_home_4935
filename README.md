# take_home_4935

# Create a new to-do item:
POST: [http/https]://{hostname}:3000/create/{toDoTitle}

# Read all to-do item:
GET: [http/https]://{hostname}:3000/read

# Update a new to-do item to completed status:
POST: [http/https]://{hostname}:3000/{toDoTitle}

# Delete a completed to-do item:
DELETE: [http/https]://{hostname}:3000/{toDoTitle}

# Search for a to-do item
GET: [http/https]://{hostname}:3000?title={toDoTitle}&status=[NEW/COMPLETED]
