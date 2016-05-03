# Building-a-Full-Stack-App-with-React-and-Express

**Original SRC:**  
https://github.com/danielstern/react-express-examplar

UPD:  
To run gulp task with nodemon use:

    $ nodemon --watch gulpfile.js --exec "gulp serve"

___


### 02 scaffolding the app

09_creating_the_initial_scaffold

    $ npm init
    $ bower init

    $ mkdir app
    $ mkdir server

    $ npm install --save express
    $ npm install --save ejs
    $ nodemon server/main.js



10_setting_up_the_gulp_file

    # npm install -g gulp
    $ npm install --save gulp gulp-live-server
    $ gulp live-server

    $ npm install --save browser-sync
    $ gulp serve


11_transpiling_our_first_jsx_script

    $ npm install --save react
    $ bower install --save react
    # npm install -g react-tools

12_bundling_the_application_with_browserify

    # npm install -g browserify
    $ npm install --save browserify
    $ npm install --save reactify
    $ npm install --save vinyl-source-stream

    $ gulp bundle
    $ gulp serve

13_creating_a_react_component

    $ gulp serve

<br/>

### 03 creating a react front end

14_displaying_a_list_of_items_with_react

    $ gulp serve

15_composing_react_classes

    $ gulp serve

16_conditionally_applying_classes

    $ gulp serve

17_implementing_a_flux_dispatcher

    $ npm install --save guid # (generate random strings)

18_adding_new_grocery_items_to_the_list

    $ gulp serve

19_using_forms_in_react_applications

    $ gulp serve

20_implementing_an_action_helper

    $ gulp serve

21_creating_a_flux_store

22_completion_of_add_item_functionality

    $ gulp serve


<br/>

### 04 completing the front end

23_deleting_items_from_the_list

    $ gulp serve

24_buying_items

    $ gulp serve

25_adding_styles_to_the_app  

    $ bower install --save skeleton

 bower_components not worked correctly on this project, and i decided to copy files to folder manually.

    $ cp bower_components/skeleton/css/*.css .tmp/

    $ gulp serve

26_conclusion

<br/>

### 05 implementing an express back end

27_creating_an_items_route

28_implementing_a-route_in_express

    $ gulp serve

    http://localhost/api/items

29_adding_body_parser_express_middleware

    $ npm install --save body-parser

30_creating_a_rest_helper

    $ npm install --save jquery

31_implementing_get_requests

    $ gulp serve

32_modifying_data_with_post_requests

    $ gulp serve


<br/>

### 06 adding mongodb

33_installing_and_running_mongodb

34_implementing_mongoose

    $ npm install --save mongoose

    $ gulp serve

35_creating_a_schema

36_implementing_the_item_model

    $ gulp serve

37_adding_patch_and_delete_to_express_and_mongoose

38_updating_editing_and_updating_items_on_the_front_end

    $ gulp serve

DONT WORK CORRECTLY  
TO DELETE ADDED ITEM, I SHOULD PRESS F5 to REMOVE ITEM WITHOUT ERRORS.  
THE REASON IS BECAUSE WHEN NEW ITEM IS CREATING it SENDING on FORM WITHOUT _id.  
I DONT KNOW HOW TO CORRECT. AND THIS IS NOT VERY INPORTANT FOR ME.

IF YOU KNOW HOW TO CORRECT, PLEASE SEND ME PULL REQUEST.
THANKS.


<br/>

### 07 making the app isomorphic

40 updating the ejs template for react

41_adding_isomorphic_functionality_to_express_using_react_and_babel

    $ npm install --save babel
    $ gulp serve
