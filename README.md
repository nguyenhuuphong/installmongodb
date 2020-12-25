# installmongodb

- mô hình dữ liệu trong mongoDB có 2 dạng: 
+ Embedded data model
+ Normalized data model

- show dbs: hiển thị database
- user db: để sử dụng database
- show colections: để chọn 1 array trong database
- db.colection.find() : hiển thị tất cả các dữ liệu trong colection đó 
- show collections: hiển thị all collection
- use mydb > db.dropDatabase() : để xóa 1 database
- use mydb > db.createCollection("name_colection") : để tạo mới 1 colection trong database đó
hoặc dùng use mydb >  db.movie.insert("name":"1") : sẽ tạo 1 colection MOVIE chứa KEY name và value 1 trong database đó 

- use mydb > db.NAME_COLECTION.drop() : để xóa 1 collection

kiểu dữ liệu trong MongoDB: string, interger, Boolean, Double, Min/Max key, Arrays, Timestamp, Obiject, Null, Symbol, Date, Object ID, Binary data, Code, Regular expression

- use mydb > db.createCollection("post") > db.post.insert({
... _id : ObjectId("507f191e810c19729de860ea"),
... title: "MongoDB Overview",
... description: "MongoDB is no sql database",
... by: "tutorials point",
... url: "http://www.tutorialspoint.com",
... tags: ['mongodb', 'database', 'NoSQL'],
... likes: 100
... })
WriteResult({ "nInserted" : 1 })
> insert có 2 method đó là insertOne(), inserMany() để chèn 1 hoặc nhiều dữ liệu cùng lúc 

- RELATIONSHIP 
1:1, 1:N, N:1 or N:N








