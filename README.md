# BookshelfDisplayReborn:

Recompiled version of BookshelfDisplay for use on more recent game versions. Targets 1.18.2 primarily, developed against JDK 8.0 for compatibility but is largely untested on other game versions.

# Original BookshelfDisplay Descriptor:

BookshelfDisplay is a SpigotMC Plugin that lets the player use bookshelves to display galleries of books.
Visit this plugin's [SpigotMC Page](https://www.spigotmc.org/resources/bookshelfdisplay.67225/) for more information.

To install, simply place the jar file in your server's `plugins` folder. You will need a single dependency, 
[ProtocolLib](https://www.spigotmc.org/resources/protocollib.1997/). (Make sure it is the latest version!) 
Place this jar in your `plugins` folder, also.

## Downloads

###### (only the newest version is maintained)

For versions <1.18.2:

##### For Minecraft 1.14.x through 1.16.X:
> [BookshelfDisplay_1.16.4-0.jar](https://github.com/Cynadyde/BookshelfDisplay/raw/master/builds/BookshelfDisplay_1.16.4-0.jar)

##### For Minecraft 1.13.x:
> [BookshelfDisplay_1.13.1-0.jar](https://github.com/Cynadyde/BookshelfDisplay/raw/master/builds/BookshelfDisplay_1.13.1-0.jar)  
  (out of date and contains bugs)

##### For Minecraft 1.12.x:
> [BookshelfDisplay_1.12.2-0.jar](https://github.com/Cynadyde/BookshelfDisplay/raw/master/builds/BookshelfDisplay_1.12.2-0.jar)  
  (out of date and contains bugs)

## Bugs & Feedback

This is intended to purely keep BookshelfDisplay functional with 1.17 1.18 and 1.19 but is only tested against 1.18.2 actively.
Feedback and bugs will likely receive minimal response as such. No new features will be added at this time.

## Permissions info:

bookshelfdisplay.*:

  description: "Grants all plugin abilities."
  default: false
  children:
    bookshelfdisplay.view: true
   
bookshelfdisplay.view:

  description: "Grants the ability to interact with bookshelves."
  default: true
