<img align="right" src="assets/HoopMapsOnBlue.png" alt="Hoopmaps logo" width="128">
<h1>Curated Runs</h1>

<p>
  Curated Runs is a smartphone app for Android and iOS dedicated to encouraging, developing, and fostering community 
through facilitating local sports.
</p>

<h2>How It Works</h2>

<h3>Structure</h3>
<p align="left">
  The app will function as a marketplace where sports facilities such as gyms, city parks and other similar entities can
  rent their spaces in the form of games. In turn, users can browse through local games, and sign up for said games.
</p>

<h3>Account Types</h3>
<p>
  There are two account types, Users and Facilities. Users are considered the default account type, and are able to 
begin signing up for games as soon as their account is created. Facility accounts must first be manually reviewed before
they can begin listing games.
</p>


<p float="right">
<img align="left" src="assets/Home_Page.png">
<img align="left" src="assets/Login_Page.png">
<br>
</p>
<p float="right">


<img align="left" src="assets/Profile_Page.png">
<img align="left" src="assets/Game_Detail_Page.png">
</p>


<div align="left" width="33%">
<h3>User Features</h3>
<li>Create account via email and password, or through third party authentication</li>
<li>Edit personal user information</li>
<li>Browse through nearby events</li>
<li>Sign up for events</li>
<li>Leave joined events</li>

<h3>Facility Features</h3>
<li>Create account via email and password</li>
<li>Edit facility information</li>
<li>Create, edit, and list events</li>
<li>View users signed up to their events</li>
<li>Can review participants that have joined their events</li>

<h2>Technology Used</h2>

<h3>Front End</h3>
<li>Flutter and Dart</li>
<li>Bloc Architecture</li>

<h3>Backend</h3>
<li>Firebase</li>

<h3>APIs</h3>
<li>Google Sign In</li>
<li>Apple Sign In</li>
<li>Google Maps</li>
</div>
<br clear="both">

<h2>Developer Instructions</h2>

<h2>Environment</h2>
<p>
  1. Add the google-services.json to android/app <br>
  2. Change local.properties in android/ and add the following:<br>
  
  ```
  flutter.compileSdkVersion=32
  flutter.minSdkVersion=21
  flutter.targetSdkVersion=30
  ```
  
  3. Make sure Android SDK is properly configured in settings.<br>
  4. Do **not** upgrade gradle tool in Android Studio for now, it leads to build issues. <br>
  *If* so change these project-settings:<br>

  Android Gradle Plugin Version --> 4.1.0<br>
  Gradle Version --> 6.7<br>
  5. Run the commands:<br>
  ```
  flutter pub get
  ```
  
  and
  
  ```
  pod install
  ``` 
</p>

<h2>Testing</h2>
<p>
  The app_test.dart contains all our current integration tests, and can be 
  found in the integration_test directory. Tests can be run individually, in 
  groups, or all at once as a batch using different run configurations via 
  command line or IDE. Our integration testing uses the Flutter integration_test 
  package. For more information, please see the 
  <a href="https://docs.flutter.dev/cookbook/testing/integration/introduction">
  Flutter Documentation</a> on the subject.
</p>

<h2>Deployment</h2>
<h3>Simulator Deployment for Internal Testing</h3>
<p>
  Set up an Android or iOS simulator using Android Studio or XCode. One the 
  simulator is up and running, Flutter should automatically recognize it in your 
  IDE. 
  <br>
  If youre running from a command line, use the command<br>
    
  ```
  flutter run -d PREFIX_OF_DEVICE_NAME
  ```
  
  Once the simulator is running, where PREFIX_OF_DEVICE_NAME is something like 'iphone' or 'pixel.' To get the name of your running simulators, use the command:
  
  ```
  flutter devices
  ```
Otherwise, just use whatever 'run' capability is present in your IDE of choice.
</p>

<h3>App Deployment for External Testing/Release</h3>
<p>
  This app is intended to be released on the Google Play and Apple App stores. As deployment information is volatile, refer to the following links:
  <br><a href="https://docs.flutter.dev/deployment/ios">iOS Deployment</a>
  <br><a href="https://docs.flutter.dev/deployment/android">Android Deployment</a>
</p>

<img align="right" src="assets/Team_Omni_Logo.png" alt="Team Omni logo" width="128">
<h2>Team Omni</h2>
<li>Adrian Armenta</li>
<li style="text-indent: 20px">Contact: adrianarmenta@csus.edu</li>
<li>Jarod Castillo</li>
<li style="text-indent: 20px">Contact: jarodcastillo2@csus.edu</li>
<li>Jared Conatser</li>
<li style="text-indent: 20px">Contact: jconatser@csus.edu</li>
<li>Malachi Dohmen</li>
<li style="text-indent: 20px">Contact: malachidohmen@csus.edu</li>
<li>Chris Inouye</li>
<li style="text-indent: 20px">Contact: cinouye@csus.edu</li>
<li>Keeghan Isted</li>
<li style="text-indent: 20px">Contact: kisted@csus.edu</li>
<li>Belle Nguyen</li>
<li style="text-indent: 20px">Contact: bnguyen7@csus.edu</li>
<li>Uriel Diaz Quintero</li>
<li style="text-indent: 20px">Contact: udiazquintero@csus.edu</li>
