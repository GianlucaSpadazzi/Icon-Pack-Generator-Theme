# Icon Pack Generator Theme
How to create an Icon Pack Generator theme - developers guide

[DOWNLOAD](https://play.google.com/store/apps/details?id=com.spada.iconpackgenerator)

Icon Pack Generator is an Android App that allows you to create your custom icon pack. Users can create icon packs with a manual configurator when they can configure some parameters, or import an image from gallery. The app will then create and install the icon pack, that can be applied with a custom launcher (Like Nova Launcher, Apex Launcher, ADW..)
But the best part of the app is the themes feature. Developers can create custom themes containing:
-a list of icon upon
-a list of icon back
-a list of icon masks
Users can choose one icon upon, one icon mask and one icon back to create an awesome icon pack!
It is better to just try the app to understand what you can achieve, or watch this video from Lone IPG theme if you want: 
[LoNe IpG](https://www.youtube.com/watch?v=MUhhDzTtFE4)

# How to create an Icon Pack Generator Theme
It is very easy to create one. After that, you can publish it on Google Play (paid or free as you wish). After that, to be listed in the themes showcase into the app, just compile this form: (I strongly suggest you to do this as you will get free advertise into the app).

* Create a new project with Android Studio (select "Add No Activity" and then API 21 as minimum API level). You can skip this if you want to add the Icon Pack Generator theme to an existing theme/app
* Put this code into the application tag of the AndroidManifest.xml file:
```xml
<meta-data
android:name="IconPackGenerator_Theme"
android:value="true" />
<meta-data
android:name="IconPackGenerator_Theme_Name"
android:value="PUT YOUR THEME'S NAME HERE" />
<meta-data
android:name="IconPackGenerator_Theme_Author"
android:value="PUT YOUR DEVELOPER NAME HERE" />
```
Change "PUT YOUR THEME'S NAME HERE" with your theme name and "PUT YOUR DEVELOPER NAME HERE" with your developer name
* If not present, create "assets" folder (click on app -> new -> directory). Under "assets" folder, create "ipg" folder. Under "ipg" folder, create "iconback", "iconmask","iconupon" folders
* Add as many images as you want in the three folders created. Name them as you want (they will be listed alphabetically into the app). The only constraint is that images must be in .png format and 192x192 pixels
* That's it! Just install the icon pack on your phone and when you're done, publish it to Google Play or where you want!

# I've published my theme on Google Play!
Congratulations! Just two quick suggestions to boost your theme's downloads
* Compile this [form](https://docs.google.com/forms/d/e/1FAIpQLSdNtV9qWWrGk2mHfWTiq3zaySZoVFLP9rlGvIjictDFYcVRvg/viewform) to be listed into the themes showcase into the app
* Put this "ipg theme" somewhere into the playstore description (also in the title if you want)
For any issue, contact me at gianluca.spadazzi@gmail.com

