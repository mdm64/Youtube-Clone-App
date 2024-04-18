# YouTube clone app

Tried to create  a video streaming app with advanced functionalities just like youtube. with the following features:
1. like advanced search feature which gives a suggestions list while making a minimum no. of API calls using the concept of debouncing and using the redux tool kit to cache the query in the search box and using that cache memory instead of making an API call for the same query again.
2. Built a Live chat, where we can read others' live comments as well as write our own using the concept of API polling we are updating the UI in intervals of every 1 second and our data layer is fetching new comments we are getting. to make it more advance or effecient so that our page do not freeze we have used redux to cache the comments loading and deleting the top comments of the cache after no. of comments reach to 100. so at one moment, we are only loading 25 to 100 comments in our UI.
3. created nested comments section just like Reddit using concept of recursion in the react component
4. created a hamburger navigation button that updates our UI when we click on it.
5. for UI styling we used tailwind CSS
6. we used youtube data api to fetch videos.
