<img align="right" src="assets/HoopMapsOnBlue.png" alt="Hoopmaps logo" width="128">
<h1>Curated Runs</h1>

<p>
  Curated Runs is a smartphone app for Android and iOS dedicated to encouraging, developing, and fostering community 
through facilitating local sports.
</p>

<h2>How It Works</h2>

<h3>Structure</h3>
<p align="left">
  The app will function as a marketplace, where sports facilities such as gyms, city parks and other similar entities can
rent their spaces in the form of games. In turn, users can browse through local games, and sign up for said games via 
in-app purchases.
</p>

<h3>Account Types</h3>
<p>
  There will be two account types, Users and Facilities. Users are considered the default account type, and are able to 
begin signing up for games as soon as their account is created. Facility accounts must first be manually reviewed before
they can begin listing games.
</p>

<div align="right" width="66%">
<img align="right" src="assets/Sign_In_Page_emu.png" alt="Sign in page" width="33%">
<img align="right" src="assets/Splash_Screen_emu.png" alt="Sign in page" width="33%">
<img align="right" src="assets/Game_Detail_Mockup_Trimmed.png" alt="Sign in page" width="32%">
<img align="right" src="assets/Game_Mockup_Trimmed.png" alt="Sign in page" width="33%">
</div>

<div align="left" width="33%">
<h3>User Features</h3>
<li>Browse through games</li>
<li>Sign up for games</li>
<li>Share Games via social media</li>

<h3>Facility Features</h3>
<li>Create and list games</li>
<li>View users signed up to their games</li>
<li>Create a deny-list of banned users</li>


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
<h3>Testing</h3>
There are no tests currently in place. When we start building them, our test framework information will go here!
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

<h2>Deployment</h2>
<p>
  Set up an Android or iOS simulator using Android Studio or XCode. One the simulator is up and running, Flutter should automatically recognize it in your IDE. <br>
  If youre running from a command line, use the command<br>
  
  ```
  flutter run -d PREFIX_OF_DEVICE_NAME
  ```

  Once the simulator is running, where PREFIX_OF_DEVICE_NAME is something like 'iphone' or 'pixel.' To get the name of your running simulators, use the command:

  ```
  flutter devices
  ```
  
</p>

<h2>Development Timeline</h2>
<h3>September</h3>
<li>User can browse through local games</li>
<li>User can view individual game details</li>
<li>User can sign in with Apple ID</li>
<li>Facilities can create an account</li>
<li>Facilities can create and list games</li>
<h3>October</h3>
<li>User can view games by map</li>
<li>User can join games</li>
<li>User can leave games</li>
<li>Facilies can view, edit, and delete game listings</li>
<li>Facilities can kick people from games</li>
<li>Facilities can set up a deny-list of Users</li>
<h3>November</h3>
<li>Users can get push notifications for games they've signed up for</li>
<li>Users can share games via social media</li>
<li>Facilities can share games via social media</li>
