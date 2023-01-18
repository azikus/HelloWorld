# HelloWorld
A simple project that says "Hello" to the whole world!

# Description
<p>The Hello World project is a simple and straightforward introduction to programming.<br>
It is designed for beginners who have little to no experience with coding and aims to familiarize them with the basic concepts 
and syntax of a programming language.<br> 
The project consists of a single script that, when executed, will print the text "Hello, World!" to the screen.</p>

# Getting started
dodati brojeve
Make sure you have the newest version of Xcode installed on your computer.
* Download the Hello World project files from the repository.
* Install CocoaPods.
* Run pod install so you can install the dependencies in your project.
* Open the project files in Xcode.
* Review the code and make sure you understand what it does.
* Run the active scheme.
You should see the text "Hello, World!" printed to the screen.<br>

Once you're comfortable with the basic concept, you can start modifying the script and experimenting with different variations.<br>
If you have any issues or need help, refer to the documentation or contact the developers for assistance.<br>
You're now ready to start your journey into the world of programming.

# Usage
In order to send a message to the whole world, you must log in with the appropriate account.
* Username: LordVoldemort
* Password: AvadaKedavra123

Important: DEV and PROD enviroment are <strong>NOT WORKING</strong> on Friday from 00;00 - 01;00 GMT due to the server maintenance.

# Architecture
dodati primjere kreiranja novog ekrana
* Hello World project is implemented using the <strong>Model-View-Controller (MVC)</strong> architecture pattern.
* Model has any necessary data or business logic needed to generate the "Hello, World!" message.
* View is responsible for displaying the message to the user, such as printing it to the console.
* Controller handles any user input or interactions and update the Model and View as needed.
* Project doesn't have a database, user interface or any other complex elements.

It serves as a starting point for those who are looking to learn programming, and it is designed to be easy to understand and modify.

# Structure 
Dodati nas primjer docs-a
* "src": The source code of the project, including the main script.
* "docs": Documentation related to the project, such as a README file or a user manual.
* "test": Test files and test suites that can be used to test the project's functionality.
* "config": Any configuration files that the project needs, such as a settings file or an environment file.
* "data": Any data files that the project uses, such as sample input or output files.

# Running the tests
<p>The Hello World project can be tested using the built-in framework XCTest.<br>
To start testing the project, you will need to create a new test target in your Xcode project, 
and then add test files to that target.<br>These test files should be placed in the "test" folder, following the project structure.
Once you have created your test files, you can write test functions using the XCTest</p>

# Deployment
Keep in mind that deploying an iOS app to the App Store requires having an Apple Developer account.

1. Click on the "Product" menu in Xcode and select "Archive." This will create an archive of your project.
2. Once the archive has been created, select it in the Organizer window and click on the "Validate" button to perform some preliminary tests on the app.
3. Once validation is complete, click on the "Distribute" button and select "Ad Hoc" or "App Store" distribution. 
This will create a signed IPA file that can be installed on iOS devices.
4. Follow the prompts in the distribution wizard to complete the distribution process.
5. Once the distribution is complete, you can use the IPA file to install the app on iOS devices

# Dependencies
Dodati cocoa pods
List of dependencies: 
* pod 'Alamofire' -> Networking library that ensures that the message reaches everyone in the world.
* pod 'AzikusAuthorization' -> Our library that serves for authorization. 
It is very important that <strong>it is maintained because it is also used by users outside the company</strong>.

# Contribution
We welcome contributions to the HelloWorld project! If you're an iOS developer and want to help out, here are some ways you can get involved:

Reporting bugs: 
- If you come across any issues while using the HelloWorld, please report them by creating a new issue on the GitHub repository.

Submitting pull requests: 
- If you have a bug fix or a new feature you'd like to add, please submit a pull request. Before submitting a pull request, 
please make sure that your changes are well-tested and that your code adheres to the Swift style guide.

Improving documentation: 
- If you notice any errors or areas of improvement in the documentation, feel free to submit a pull request with your changes.

Providing feedback:
- If you have any feedback or suggestions for the HelloWorld project, please let us know by creating a new issue or by sending an email to the project maintainer.

Odvojit svaki u zaseban chapter
# Useful links
* Task board: www.helloworld/jira.com
* Design: www.helloworld/figma/design.com
* API docs: www.helloworld/azikus/APIdocs.com
