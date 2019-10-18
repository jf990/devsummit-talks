<!-- .slide: data-background-size="cover" data-background="../../template/img/2019/devsummit-berlin/bg-title.png" -->

<div class="flush-left">
<h1 style="text-align: left; font-size: 3em;">AppStudio for ArcGIS</h1>
<h2 style="text-align: left; font-size: 2em;"> Developing Cross-Platform Native Apps</h2>
  <p style="text-align: left; font-size: 1em; color: #E6DD56;">John Foster
  <a href="https://github.com/jf990" target="_blank">@jf990</a></p>
  <p style="text-align: left; font-size: 1em; color: #E6DD56;">Mary Harvey
  <a href="https://github.com/maryharvey" target="_blank">@maryharvey</a></p>
  <p style="text-align: left; font-size: 0.75em; color: #E6DD56;">slides: <a href="https://github.com/jf990/devsummit-talks/app-studio-for-developers/"><code>https://github.com/jf990/devsummit-talks/app-studio-for-developers/</code></a>
</div>

---

<!-- .slide: style="line-height: 6rem;" data-background="../../template/img/2019/devsummit/bg-2.png" -->

## Agenda

1. 🌐- What is AppStudio? Developer Edition?
2. 👩‍🚀- Who is using it? For what?
3. 📆- Customizing apps
4. 💯- Developer patterns
5. 🤹‍- Deployment

---

<!-- .slide: style="line-height: 4rem;" data-background="../../template/img/2019/devsummit/bg-6.png" -->

### AppStudio Developer Edition

* Low code solution for creating native location-based apps
* using ArcGIS
* using ArcGIS Runtime SDK for Qt
* Cross-platform (mac, windows, linux desktops, ios, android)

---

<!-- .slide: style="line-height: 4rem;" data-background="../../template/img/2019/devsummit/bg-6.png" -->

### AppStudio Developer Edition

* AppStudio attempts to address:
   - using ArcGIS across native devices
   - with a single codebase
   - providing templates to address the most common mapping use cases
   - low code customization
   - leveraging Qt/QML to customize to the max, even starting from scratch
   - build for all devices in the cloud and download the final app bundle

---

<!-- .slide: style="line-height: 4rem;" data-background="../../template/img/2019/devsummit/bg-6.png" -->

### Native app development

* performance
* development tooling
* online and offline
* access to the device capabilities (camera gps low-level native APIs)
* deploy to app store

---

<!-- .slide: style="line-height: 4rem;" data-background="../../template/img/2019/devsummit/bg-6.png" -->

### Native app development

...but native is hard

* lower level means higher knowledge
* bigger foot guns
* much more code
* cross platform options
   * separate codebase (and dev team) per target platform: Swift, Java, Kotlin, C#
   * flutter, ionic, react native: OK, javascript, but still have to code separately for device control
   * Xamarin: C#/.NET

---

<!-- .slide: style="line-height: 4rem;" data-background="../../template/img/2019/devsummit/bg-6.png" -->

### Who is the target user for AppStudio?

- _GIS Professional_ who wants to config an app
   - appstudio has templates with config
   - fonts, icons, colors, settings
   - test on multiple devices
   - share with enterprise users
   - deploy to app stores

- _Casual developer_ who wants simple location, write a customize app

- _Professional developer_ comfortable with Qt/QML

*** In general, AppStudio + QML makes it easier to write and deploy native apps
_less code_
_easier_

---

<!-- .slide: style="line-height: 4rem;" data-background="../../template/img/2019/devsummit/bg-6.png" -->

### ArcGIS integration

- Runtime SDK for Qt
- ArcGIS Online/Enterprise

Bring the power of ArcGIS to your app

---

<!-- .slide: style="line-height: 4rem;" data-background="../../template/img/2019/devsummit/bg-6.png" -->

### What has been built with AppStudio?

- Survey 123
- Quick capture
- ArcGIS Companion
- Esri support app
- Esri labs projects - show a few screenshots
- Esri professional services - show a few screenshots
- Customer apps - show a few screenshots

---

<!-- .slide: style="line-height: 4rem;" data-background="../../template/img/2019/devsummit/bg-6.png" -->


### Productivity tools (stuff you get when you install it)

- download for free, install on mac win linux
- desktop app
- app templates
- app samples
- enterprise templates
- appstudio player
- cloud make
- Qt Creator

---

<!-- .slide: style="line-height: 4rem;" data-background="../../template/img/2019/devsummit/bg-6.png" -->

### caveats

1. Qt Creator dup if you install Qt separately
2. ArcGIS Runtime SDK for Qt is installed separately
3. No C++
4. No kits - use Cloud Make

---

<!-- .slide: style="line-height: 4rem;" data-background="../../template/img/2019/devsummit/bg-6.png" -->

### Cost and License

* it's actually free to download and start developing
* two levels:
   - App Studio
      - All the tools
      - distribute apps at the Runtime Lite level
      - deploy apps with ArcGIS Online/Enterprise
   - App Studio Developer Editions
      - unlock with account login
         - ArcGIS Online entitlement
         - Developer Builder plan
      - All the tools PLUS Cloud make
      - Enterprise templates and source code
      - distribute apps Runtime license key
      - deploy apps with ArcGIS Online/Enterprise and app stores
* follows ArcGIS Runtime licensing
* requires either an Org License OR a Developer Builder plan (or higher)

= show the Org licensing page screenshot
= show the developer account Builder page and PAYG credits

---

<!-- .slide: style="line-height: 4rem;" data-background="../../template/img/2019/devsummit/bg-6.png" -->

### Demo #1 AppStudio desktop app

- run the AppStudio desktop app
- login, explain "developer edition"
- show and explain the available templates
- show the available enterprise apps
- show the available samples
- create a template app
- demo tool palette: files, duplicate, delete, edit, run, settings
- demo the basic template how it works
- demo changing some app settings (color, font, title) = use settings app
- run the app on desktop only.
== Should we do a cloud make and demo how that all works?
= demo offline map package?
= be sure to share all maps public!

Player is available from app stores
Source code to AppStudio player is available, you can customize it!
LINK?

---

<!-- .slide: style="line-height: 4rem;" data-background="../../template/img/2019/devsummit/bg-6.png" -->

### What about QML?

- what is Qt? slide on Qt background, history
- what is QML?
- how does JavaScript fit in all this?
- quick show of Qt/QML doc pages
- QML learning resources

---

<!-- .slide: style="line-height: 4rem;" data-background="../../template/img/2019/devsummit/bg-6.png" -->

### ArcGIS Runtime SDK for Qt

- show landing page
- Guide
- Samples
- API Reference

---

<!-- .slide: style="line-height: 4rem;" data-background="../../template/img/2019/devsummit/bg-6.png" -->

### AppStudio Extend Apps

- go over some of the doc pages

- Explain how to license
  - Developer Essentials plan with Runtime Lite license
  - Developer Builder plan with Runtime Basic license
  - ArcGIS Online Org with AppStudio Developer Edition

---

<!-- .slide: style="line-height: 4rem;" data-background="../../template/img/2019/devsummit/bg-6.png" -->

### Project structure

- review project structure
- images
- assets
- QML files

---

<!-- .slide: style="line-height: 4rem;" data-background="../../template/img/2019/devsummit/bg-6.png" -->

### Demo #2

- let's build a simple app with some cool ArcGIS features
- web map
- toolbar
- place search +suggestions (use Nearby?)

Run it

---

<!-- .slide: style="line-height: 4rem;" data-background="../../template/img/2019/devsummit/bg-6.png" -->

## Deployment

- go over Runtime licensing
- intro to Cloud Make
- talk about deploying native apps, app stores, ad hoc deployments

---

<!-- .slide: style="line-height: 4rem;" data-background="../../template/img/2019/devsummit/bg-6.png" -->

## Demo #3

- Cloud Make the app we were demoing
- deploy it on some devices

- Cloud Make it

- Run it on device?
- offline?
- device features?

---

<!-- .slide: style="line-height: 4rem;" data-background="../../template/img/2019/devsummit/bg-6.png" -->

### Closing slides

- there's a lot here
- play with the samples
- get on GeoNet
- visit us at the booth

### How do I get it?

- https://developers.arcgis.com
- https://www.esri.com/en-us/arcgis/products/appstudio-for-arcgis/resources

---

<!-- .slide: data-background="../../template/img/2019/devsummit/bg-rating.png" -->

---

<!-- .slide: data-background="../../template/img/2019/devsummit/bg-esri.png" -->
