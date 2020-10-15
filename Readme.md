How to Execute it?

- Import the JSON collection in postman app
- Import the environment file as well 
- Start the collection Runner for the folder 
- Upload the data.csv file
- Now Run the collection 
- See Results on the Collection Runner

Newman 
Run the following command in the folder where you have all the JSON files,

newman run Cloudways.postman_collection.json -e cloudways.postman_environment.json -d data.csv -r htmlextra --reporter-html-export

