# Sticky Mobile Menu - Atom for Gantry
This project enable control over the default mobile menu behavior within the Gantry templating framework. **Sticky Mobile Menu** was created to keep the current selected sub menu items focused within the hamburger menu / offcanvas section. Hence, instead of showing the root menu items, the current active sub menu items are displayed. Furthermore, it provides an easy, user friendly and GUI assisted configuration and integration. In the current revision the following CMSs are supported:
* Joomla
* Wordpress
* Grav

## Prerequisites
* CMS (Joomla, Wordpress, Grav)
* Gantry Templating Framework and Theme

## Download
Choose the correct download for your target platform. The Joomla Plugin System is supported for all Gantry themes globally or locally for the templates Helium and Hydrogen. The latest Atom version is **v1.0.9**.
___
**Default Atom:**
[English](https://github.com/thexmanxyz/Sticky-Mobile-Menu-Gantry/releases/download/v1.0.9/smm.atom.only.EN.v1.0.9.zip) / [Italian](https://github.com/thexmanxyz/Sticky-Mobile-Menu-Gantry/releases/download/v1.0.9/smm.atom.only.IT.v1.0.9.zip) / [German](https://github.com/thexmanxyz/Sticky-Mobile-Menu-Gantry/releases/download/v1.0.9/smm.atom.only.DE.v1.0.9.zip)

**Legacy Atom - Gantry <5.3.2:**
[English](https://github.com/thexmanxyz/Sticky-Mobile-Menu-Gantry/releases/download/v1.0.9/smm.atom.only.legacy.EN.v1.0.9.zip) / [Italian](https://github.com/thexmanxyz/Sticky-Mobile-Menu-Gantry/releases/download/v1.0.9/smm.atom.only.legacy.IT.v1.0.9.zip) / [German](https://github.com/thexmanxyz/Sticky-Mobile-Menu-Gantry/releases/download/v1.0.9/smm.atom.only.legacy.DE.v1.0.9.zip)

**Joomla Plugin - All Templates (Global):**
[English](https://github.com/thexmanxyz/Sticky-Mobile-Menu-Gantry/releases/download/v1.0.9/smm.j3.global.EN.v1.0.9.zip) / [Italian](https://github.com/thexmanxyz/Sticky-Mobile-Menu-Gantry/releases/download/v1.0.9/smm.j3.global.IT.v1.0.9.zip) / [German](https://github.com/thexmanxyz/Sticky-Mobile-Menu-Gantry/releases/download/v1.0.9/smm.j3.global.DE.v1.0.9.zip)

**Joomla Plugin - Hydrogen:**
[English](https://github.com/thexmanxyz/Sticky-Mobile-Menu-Gantry/releases/download/v1.0.9/smm.j3.hydrogen.EN.v1.0.9.zip) / [Italian](https://github.com/thexmanxyz/Sticky-Mobile-Menu-Gantry/releases/download/v1.0.9/smm.j3.hydrogen.IT.v1.0.9.zip) / [German](https://github.com/thexmanxyz/Sticky-Mobile-Menu-Gantry/releases/download/v1.0.9/smm.j3.hydrogen.DE.v1.0.9.zip)

**Joomla Plugin - Helium:**
[English](https://github.com/thexmanxyz/Sticky-Mobile-Menu-Gantry/releases/download/v1.0.9/smm.j3.helium.EN.v1.0.9.zip) / [Italian](https://github.com/thexmanxyz/Sticky-Mobile-Menu-Gantry/releases/download/v1.0.9/smm.j3.helium.IT.v1.0.9.zip) / [German](https://github.com/thexmanxyz/Sticky-Mobile-Menu-Gantry/releases/download/v1.0.9/smm.j3.helium.DE.v1.0.9.zip)
___

## Automatic Installation (Joomla only)
1. Download the Plugin of the *Sticky Mobile Menu Atom* for **Hydrogen, Helium or Global** installation.
2. Install it over the Joomla Plugin System.

*If you install the plugin globally be aware that the resource location changes to `/media/gantry5/engines/nucleus`*

## Manual Installation
1. Download the **Default or Legacy Package** of the *Sticky Mobile Menu Atom*. If you are using Gantry **<5.3.2** please use the **Legacy Package** for compatibility reasons.
2. Extract the files.
3. Copy the `.html.twig` and the `.yaml` file to your particle folder `/[GANTRY_THEME]/custom/particles`. Please check the [listing](https://github.com/thexmanxyz/Sticky-Mobile-Menu-Gantry#cms-template-folder) below to determine where the template folder for your CMS is located.
4. Copy the `.js` file to the folder `/[GANTRY_THEME]/custom/js`. Create the folder if it does not exist.

## CMS Template Folder
Please be aware that the template folder path varies in dependence of the used CMS. Here is a list of the folders for the different platforms:

### Wordpress
`/wp-content/themes/[GANTRY_THEME]`

### Joomla
`/templates/[GANTRY_THEME]`

### Grav
`/user/data/gantry5/themes/[GANTRY_THEME]`

## Configuration
1. Go to your Gantry templating backend (e.g. Extensions/Templates).
2. Switch to **Page Settings** and add the new appearing Atom called **Sticky Mobile Menu** either globally to your site (**base outline**), to a specific template or page by dragging it to the designated section.
3. Configure the appearance according to your favor.
4. [Optional] The download package contains the JS file of the project. You can embed it over the backend configuration if you do not want to use the default CDN. If you chose automatic installation the file is already there.

## Supported Parameters and Atom Options
* Memorize menu selection
* Switch between top and sub menu priority
* JS priority and placement (head or footer)
* JS configuration
  * Remote, Local and Default
* JS execution
  * Asynchronous
  * Deferred

## Showroom
Insight of the *Sticky Mobile Menu - Gantry Atom* configuration:

**Backend (1)** - *[Javascript](/screenshots/backend_js.png)*

![1](/screenshots/backend_js.png)

## Future Tasks
- [ ] add more languages

## Known Issues
* none

## Dependencies
[Gantry Framework](http://gantry.org/)

## Credits
Thanks to the [Gantry](https://github.com/gantry) team for providing a modern templating framework.

## by [thex](https://github.com/thexmanxyz) | [gantryprojects](https://gantryprojects.com)
Copyright (c) 2018, free to use in personal and commercial software as per the [license](/LICENSE).
