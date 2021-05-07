### TrySwitching

> TrySwitching is a serrvice enabling users to switch their providers.

We are using switching providers for:
- Broadband (done)
- Energy (done)
- Charging electric cars (work in progress)


### Tech

The tool for creating the product is [HubSpot](https://www.hubspot.com/)
The project id is 8966293.

You can downoland the project locally and open it in your IDE or you can open it in HubSPot's IDE. To do this navigate to Marketing -> Files and Templates -> Design Tool.

### Project structure

To get into project's theme go to 'try-switching' folder in project's root.

#### Assets 
Folder consist fonts, css files and js files. If you want to add a css file you must remamber to style.css. Fonts are declared in main.css.
Styles -> Components - folder consist reusable elements used in different modules. 
Styles -> Modules - folder consist styling for global modules
Styles -> Templates - folder consist styling for dynamic themes
Styles -> Utils - folder consist mostly 3rd party css rules
JS folder consist subfolder for every template with JS functionality named by page's template ( f.e. JS -> homepage ).
JS -> step_two and ste_three flies are responsible for 'Help me choose' funcionality in main modal component. 
JS -> addressPopup - file consost validation and cashing user's postcode input in main search form.
JS -> getBlogs - file consist HubSpoot's API function for receiving blogs.
JS -> graphQL - file consist POST call to 3rd party StickeeAPI for receiving broadband deals for specyfic postcode.
JS -> postcoderAPI - file consist GET call to 3rd party PostCoderAPI for receiving adresses for specyfic postcode.
JS -> postcoderEmail - file consist POST call to HubSpots submissions.


#### Layouts
In this folder are located html templates for most outer components for pages. Here you can edit <head> and <body> tags. 

#### Themes 
In this foled are themes for pages with dynamic content (blog listing and blog post)

#### Other
The files outside of any of those folers should have .html extension (Despite the theme.json which is a config file). These files are custom static pages templares.

