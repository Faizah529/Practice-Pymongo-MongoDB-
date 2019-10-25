# Practice Case Pymongo (MongoDB)

In this repository, it contains how to create a new collection  using projection and validation of the collection:

**Outline:**
- Create a new Collection with the name **clean_movies** where the documentation comes from the collection **movies_initial** and the format and Valuesnya must be exactly same as collection **Movies**.
- Validate documents that have been created at **clean_movies**.

**Collection(table):**
- movies
- movies_initial

**Instructor :**
1. Create **MongoDB Cluster** using MongoDB atlas. 
2. In this case using cluster : 
> connect database that contains collection **movies_initial**:<br>
> "mongodb+srv://admin1234:12345@cluster0-miqju.gcp.mongodb.net/test?retryWrites=true&w=majority"<br>
> connect database that contains collection **movies**:<br>
> "mongodb+srv://userstudent:admin1234@cluster0-nnbxe.gcp.mongodb.net/test?retryWrites=true& w=majority"
3. Get client of this cluster.
4. Get database of client.
5. Get collection of database.
6. After getting collection of database than you can follow the steps in Python jupyter notebook.

