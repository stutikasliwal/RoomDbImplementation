# RoomDbImplementation

### Dependency - 
```
implementation "androidx.room:room-runtime:2.2.4"
kapt "androidx.room:room-compiler:2.2.4"
implementation "androidx.room:room-ktx:2.2.5"
```
### top level dependency- 
```
plugins {
    id 'kotlin-kapt'
}
```

## Room database pros- 
1. Abstraction over SqLite
2. Less Boilerplate
3. Compile time verification over SQL queries.

## Components of ROOM DB- 
1. Entity (Tables) - Name of table
2. Dao (Data Aaccess Objects)- To access data objects we create CRUD operations.
3. Database
4. Type convertors
5. Migrations
