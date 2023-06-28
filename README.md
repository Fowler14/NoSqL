# NoSqL


### During part one when I went to update the database with "Penang Flavours" I did not inlcude all the info that was given. I later realized this when I went to do the analysis on the 2nd part. I ended up more or less restarting just to make it easier. On my 2nd attempt when I run the code below I get a result of zero this is incorrect as the database was then updated to remove all instances of 'Dover' the original result of the the code below was 994. 

### query = {"LocalAuthorityName":"Dover"}
### count = db.establishments.count_documents(query)

### print(count)
