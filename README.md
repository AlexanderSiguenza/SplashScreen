# SplashScreen
Este proyecto es un ejemplo de pantalla de Bienvenida en Android

Los pasos a seguir son los siguientes :

1- Crear el tema que se le dara a la pantalla de bienvenida.
   res/values/themes/themes.xml     
      
<style name="ThemeSplash" parent="Theme.MaterialComponents.Light.NoActionBar">
	    <item name="colorPrimary">@color/colorPrimarySplash</item>
	    <item name="colorPrimaryDark">@color/colorPrimaryDarkSplash</item>
	    <item name="colorAccent">@android:color/white</item>
</style>

2- Agregar los colores personalisados del tema:
    res/values/colors.xml
    
    <color name="colorPrimary">#D81B60</color>
    <color name="colorPrimaryDark">#BB1658</color>
    <color name="colorAccent">#304FFE</color>
    <color name="colorPrimarySplash">#00C853</color>
    <color name="colorPrimaryDarkSplash">#00993F</color>
    <color name="colorAccentSplash">#E65100</color>

 3- Agregar las imagenes : res/mipmap 
    - udb.png
    - user.png

4- Crear el fondo de pantalla personalizable 
   res/drawable/bg_splash_gradient.xml   
  
    <gradient
        android:angle="90"
        android:endColor="@color/colorAccent" />
        
5- Crear layout (activity_main , activity_splash)

6- Crear y modificar las clases (MainActivity, ActivitySplash)

7- Modificar AndroidManifest.xml


   
   
