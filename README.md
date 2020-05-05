Author

    Dan Kariuki

Application Name

    GoneIn60

Description

    An Application which gives users the ability to post/pitch a statement, comment on other statements, register, login into           their profiles, and submit updates on their profiles as well as other features.

Developers Contact

    Dankariuki0101@gmail.com

Known Bugs

    Server error, but it works.

These are the behaviours/features that the application implements for use by a user.

As a user I would like to:

    View the pitches I have created in my profile page.
    
    Be signed in for me to leave a comment
    Submit a pitch in any category.
    Comment on the different pitches and leave feedback.
    See the pitches other people have posted.
Specifications
Behaviour 	                Input 	                    Output
Display pitches categories| On page load 	    |List of various categories 
Display tabs with category| On Tab link click 	|Clickable links to open pitches by category
Display profile on request| Click profile page 	|Redirected to a page with your profile
Display pitches on request| On page load 	    |Each pitch displays author, title, pitch, date comment tab
To add a pitch on request | Click an add pitch 	|Redirected to the pitch collection form
SetUp / Installation Requirements
Prerequisites

    python3 and above
    pip3
    virtualenv

Cloning

    In your terminal:

      $ git clone https://github.com/Buttonupd/GoneIn60/
      $ cd GoneIn60

Running the Application

    Creating the virtual environment

      $ Virtualenv env. Note env is the name we give our virtual environment
      $ source env/bin/activate to activate the virtual environment
      

    Installing Flask and other Modules

      $ see Requirements.txt

    To run the application, in your terminal:

      $ chmod +x start.sh
      $ ./start.sh


Technologies Used

    Python3.6
    Flask
