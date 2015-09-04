# Building-a-Full-Stack-App-with-React-and-Express
[Pluralsight] Building a Full-Stack App with React and Express [2015, ENG]



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
