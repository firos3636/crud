## CRUD-enabled Node.js app using Express and MySQL to manage a name list.
### Features:

✅ Add a name  
✅ Get all names  
✅ Get a name by ID  
✅ Update a name  
✅ Delete a name  

To install Node.js on your system, use the following commands:

```
curl -fsSL https://deb.nodesource.com/setup_18.x | sudo -E bash -
sudo apt install -y nodejs
```

Check version:

```
node -v
npm -v
```

### Change database host in database.env     
```
DB_HOST=RDS_ENDPOINT
DB_USER=USER
DB_PASS=PASS
DB_NAME=node
```

## Set Environment
```
cd node_CRUD
npm init -y
npm install express mysql dotenv
```

### Start the Server

```node server.js```


### Manually test mysql connection
`mysql -h database.cdu0wy4s26zn.ap-south-1.rds.amazonaws.com -u root -p`

