# Budget-Tracker

## GOAL

The goal of this PWA assignment was to add functionality to starter code that would enable a user to add expenses or deposits to a budget tracker offline. Any information added offline should also appear in the app once the user is back online. 

## PROCESS

As with any assignment, the initial steps include closely studying the requirements, and then slowly studying any given starter code, trying to make sense of it all. I then went back to the last week's material and activities and reviewed those. 

With the help of my tutor, I added the additional files to the repository's file structure, which were: in the public folder, an indexedDB.js file, a service-worker.js file, and a manifest-webmanifest.js file. I also knew that I would have to edit some of the starter code. 

After taking several notes that helped me in determining what my steps for coding would be, I started working on the manifest.webmanifest.js file. This would be the "easiest" of all of the remaining files, as it doesn't deal with logic. 

At this point, I also added a link to the manifest file in index.html. 

I then moved onto the service-worker file. I found activities from class that gave me a good template for the service-worker code. 

The last big snippet of code I tackled was in the indexedDB.js file, which proved to be much more challenging. For this particular part, I used the help of my tutor and my fellow classmates. 

In order for everything to work as desired, I added some additional code to the index.html file, connecting it to both the indexedDB and the service-worker files. 

Lastly, I looked over the code to fix any spelling and semantic errors, and tested the app several times, both online and offline, making sure that anything I entered offline also showed up when I was back online. 

Here is a walkthrough-video of the Budget-Tracker app:

[Budget-Tracker Walkthrough Video](https://drive.google.com/file/d/1eEKP-QQBQmoYF07VbM04RaVGX76y2VLc/view)

## USAGE

The Budget-Tracker app is deployed in Heroku with the [Budget-Tracker Heroku link](https://enigmatic-chamber-82572.herokuapp.com/).

The user can also access the app in VS Code after the Budget-Tracker repository has been cloned from GitHub. After installing node modules and all of the necessary dependencies, simply start the router using "npm run start". This will start the app in localhost:3001 in the user's browser. 

## CONCLUSION

After many weeks of very overwhelming assignments, this one seemed a bit more straightforward. It was still challenging, but figuring out its missing pieces was a bit easier. As usual, working with other people proved to be invaluable. Part of the code that I wrote came straight from the activities in class and worked well, but I intend to go back and study it further, as some of the logic is a little obscure to me still. I believe that PWAs could be really important, especially in places that do not have instant and reliable internet service, and I look forward to seeing what happens with them in the future. 
