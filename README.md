# Description

A command-line tool to prune your grocery list and add snacks and other ingredients.

A pre-requisite is to be using a CalDAV calendar todo list to store your grocery list. 

I'm planning to use Mela to generate the bulk of the groceries in my list, but you could populate your list with groceries any other way you like.

This tool, Fragola, is meant to easily remove unneeded groceries from the list and then add snacks or other ingredients. A final post-processing step, if you will.

This tool is in development. In the future, it would also be nice to sort the list by store department: i.e., produce, dairy, deli, etc.

# Getting started

1. Clone this repository
```shell
git clone 
```

2. Run `bundle install`

3. Create an ENV file with the following items
```txt
CALDAV_HOST=<your caldav host url>
CALDAV_USER=<your caldav username>
CALDAV_PW=<your caldav password>
GROCERY_LIST_URI=<url to your grocery todo list calendar>
```

4. Make the `run` file executable. `cd` into the cloned fragola directory and `chmod +x run`

5. Run the grocery list organizer from the fragola directory
```shell
./run
```