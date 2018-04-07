# CS590 - Mobile ICP 3

## Lab Description:

### This lesson helps in understanding some important aspects of android such as fetching JSON data from APIs, parsing the JSON data, handling errors, using the AsyncTask Class and some Java elements along with usage of List View.

Each list item (1-5) is an accomplished TODO item in the Android Studio solution

1.  Create an HTTP Get Request
2.  Verify that we received a 200 - OK response from the server and read the response into a StringBuilder
3.  a.	Parse the StringBuilder into a JSONObject
	b.	Create a JSONArray of the JSONObject
	c.  Iterate through the JSONArray and create a temporary JSONObject for the child JSONObject named "properties"
	d.  Assign temporary variables from the JSONObject and new up an EarthQuake object
	e.  Add the EarthQuake object to the list of EarthQuake objects
4.	Create a browser intent to open the EarthQuake object's url in the Android web browser
5.  Add the Android App permission to use the internet
