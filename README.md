codetribe Data mongodb 

## you run this code to get started
1. ## to open mongoDB shell

```bash
mongosh
```

1. ## create the database
   -use Codetribe

2. ## creating facilitators collection
to create a collection of facilitators
  db.facilitators.insertOne({
  Name: "edmond",
  Location: "tembisa",
  Course: "full-stack"
})

3. ## creating trainees collection
to create a collection of trainees
  db.trainees.insertOne({
  Name: "mukona",
  Location: "tembisa",
  Facilitator: "edmond"
})

4. ## creating projects collection
to create a collection of projects
  db.projects.insertOne({
  Name: "mongoDB",
  Course: "full-stack",
  Lesson: "one"
})

## Images
![Screenshot]
![Screenshot 2024-11-25 153324](https://github.com/user-attachments/assets/3e030c91-6d23-4f1e-b0f7-9ec7097d61b7)


## Verifying the Data
 use the following commands:
View all documents in the Facilitators collection:
      ```bash
      db.Facilitators.find().pretty()
      ```

View all documents in the Trainees collection:
      ```bash
     db.Trainees.find().pretty()
      ```
 
