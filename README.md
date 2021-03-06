# The Plant Shop
A simple plant lover's forum, demonstrating the usage of authorization (login/logout/signup) process for user access.

## How It's Made:

**Tech used:** HTML, CSS, JavaScript, Express, MongoDB, Mongo Client

I built The Plant Shop Forum forum using express framework. Using passport connection, I created a local login database located in a mongodb collection created for this specific demo. Using the body-parser to isolate specific data, I was able to parse what information should be stored and communicated between my routes, server, main javascript and ejs.

<!-- ## Optimizations
I further optimized the forum by adding a plant lookup API that displays an image and a description of the plant looked up if it's in the database. If the plant is not identifiable (not in the database) it will return flower not detected and direct the user to the option of adding the flower to a [mongo] database adding a name, photo, and descripition.  -->

## Lessons Learned:
- The importance of being aware of the IP and whitelist for a variety of location access. The power of "save" vs "insertOne" when working with database arrays. In making this change I was able to correct a deprecation error. Using mongoose.set outside of the function to address adding the most updated UrlParser and unifiedTopology to correct deprecation errors surrounding the usage of the application on various versions.
-  I usefulness of hard coding information using an object in the post section of my routes whilst connecting to my ejs file. 

![Screen Shot 2022-06-07 at 4 03 42 PM](https://user-images.githubusercontent.com/22268455/172472212-fbbde60c-bf7f-4094-acd9-4089d6b01127.png)

![Screen Shot 2022-06-07 at 4 02 41 PM](https://user-images.githubusercontent.com/22268455/172472084-9e29356a-4388-47a5-9c78-6c7c42971d99.png)


