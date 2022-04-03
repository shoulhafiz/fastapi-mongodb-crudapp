# fastapi-mongodb-crudapp
fastapi-mongodb-crudapp.
package required: pip install pymongo fastapi uvicorn
How to start uvicorn server with auto reload after defined app in index.py: uvicorn index:app --reload
initially received internal server error connecting to mongodb local collection, fixed after disabled the ssl conection on mongodb via MongoDb client.
