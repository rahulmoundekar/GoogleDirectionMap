# GoogleDirectionMap
An API is a set of methods and tools that can be used for building software applications.

We are going to create 3 files for this tutorial.

1. Html File

  The html file will contains the screen layout that is designed for users to enter the starting point and destination point. Users will be able to perform a query of the location and clear the entries.

2. Style CSS File

  The css file will be used to style the html page screen.

3. Javascript File

  The javascript file contains all the functions needed to make it happen.
  
  If you notice carefully on above codes under the head tag, you will notice that I have included two external javascript files. The first one is JQuery file, I found it is easier to use this script to manipulate the DOM of HTML. You can exclude this one if you want to, what you need to do is to modify any code starting with the $ (dollar sign) to use the native javascript code. The second script is the API Google Map script. You are required to enter the API Key for this script. If you do not have any Google Account, please register first. It is completely free. Once your account is registered you can get your API key on the following url.
  <script type="text/javascript" src="http://maps.google.se/maps/api/js?key=Your_key"></script>
  
    note :When you request an API Key, you have an option to restrict the script source origin (web URL), this is actually important so that only you can use the API Key. Note: there is a limited number of uses to access the Google API. Therefore restriction is highly recommended.
