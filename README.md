# Integrate_Web_to_Android

![alt text](https://3.bp.blogspot.com/-Zv8E3PsWgPE/V0A3c86hKoI/AAAAAAAAAIw/ZQJu1ApHQPoRzgKlvxusFdPyUqYdoXhfwCLcB/s1600/application%2Bwork%2Bsharecodepoint.PNG)

## Step 1: Create a New Project <br />
  -Open a new project. <br />
  -We will be working on Empty Activity with language as Java. Leave all other options unchanged. <br />
  -Name the application at your convenience. <br />
  -There will be two default files named activity_main.xml and MainActivity.java. <br />

## Step 2: Set-up activity_mian XML File <br />
  -Delete the default TextView  <br />
  -Add a WebView <br />

Code: <br />
```
<WebView
        android:id="@+id/idWebView"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content">

</WebView>
```

## Step 3: Add HTML, CSS, and JS file <br />
```
 C:\Users\Your-Computer-Name\AndroidStudioProjects\Your-Folder-Name\Project\app\src\main 
 ```
  -Add create a assets folder (note: do not change the assets with asset, Assets or any other then it's not works) <br />
  -Add your HTML CSS & JS file and it ready to go.

## Step 4: Change the MainActivity file <br/>
```
import the WebView webView; 
```
Get the id of that WebView by <br/>
```
webView=findViewById(R.id.idWebView);
```
Call the HTML file <br/>
```
webView.loadUrl("file:///android_asset/index.html"); 
```
