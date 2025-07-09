# WIP
## To Do
* Migrate codes to this new repo
* Translate the code to english
* Migrate readme
* Migrate categorize_produto function
* Create dimentional diagram image
* Anonymize variables, function, paths names
* Reformulate raspberry setup readme
* Add folder struct on readme
* Unify fato_2023 and 24 in just one function
* Migrate sensitive data to .env
* Add code on sql folder

## Jira Backlog
#### Task Id 
* 15 - Migrate code (WIP)
* 22 - Document queries

## Notes
* Before running the 'recreate_views' script, validate that the table/views is added to metadata_object_dependencies.

# Python & SFTP Command Descriptions

## Python Package Management

- `pip install -r requirements.txt`  
  ➤ Installs all Python packages listed in `requirements.txt`.

- `pip install --upgrade psycopg2`  
  ➤ Upgrades the PostgreSQL adapter for Python to the latest version.

- `pip install --upgrade python-dotenv`  
  ➤ Upgrades the package used to load environment variables from `.env` files.

---

## SFTP (Secure File Transfer Protocol)

- `sftp user@ip`  
  ➤ Connects to a remote server via SFTP using the specified user and IP address.

- `pwd`  
  ➤ Shows the current directory on the remote server.

- `lpwd`  
  ➤ Shows the current directory on your local machine.

- `put -r <c:\folder path\>`  
  ➤ Recursively uploads a local folder to the remote server.