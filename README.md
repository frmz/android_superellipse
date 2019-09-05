# Android-Canvas-Squircle


![A set of squircles](https://github.com/MicroRJ/Android-Canvas-Squircle/blob/master/s_sample1.png)
![A set of squircles](https://github.com/MicroRJ/Android-Canvas-Squircle/blob/master/s_sample2.png)

A FULL squircle for the Android Canvas, no tricks. You can customize it and modify it. 

# Instructions

Step 1. Add the JitPack repository to your build file

Add it in your root build.gradle at the end of repositories:


	allprojects {
		repositories {			
			...
			maven { url 'https://jitpack.io' }
		}
	}

  
Step 2. Add the dependency


	dependencies {
		implementation 'com.github.MicroRJ:Android-Canvas-Squircle:1.0'
	}



# Example

	 <com.microdevrj.superellipse.custom_superellipse_views.SuperEllipseImageView
		android:layout_width="200dp"
		android:layout_height="200dp"
		android:layout_gravity="center"
		android:padding="64dp"
		app:colorFill="@color/colorFill"
		app:colorStroke="@color/colorStroke"
		app:paintStyle="fillAndStroke"
		app:strokeWidth="6dp" />



Squircles are a highly requested feature that haven't been added to Android natively, so here you have it, plain and simple and efficient. 

Make sure to let me know if you used my code, I'd be excited to see what projects you're using it on!
And if you'd like to credit me I would highly appreciate it. 

If you like this project and want to motivate me, give it a star!

# A SQUIRCLE IS NOT A ROUNDED SQUARE
