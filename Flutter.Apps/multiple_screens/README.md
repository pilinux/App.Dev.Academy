## multiple_screens

Navigate pages demo app


### About the app

- navigating from one page  to another
- using states to browse the last visited pages


### Extra information

- every time a new page is called, `initState()` is called automatically and for
only one time
- if anything needs to be executed while a new page loads, add that function in
`initState()`
- if anything needs to be executed before destroying that page, add that
function in `deactivate()`


### Screenshots

Home | About Us | Contact
-----|----------|--------
![home_page][01] | ![about_us][02] | ![contact][03]


[01]: https://cdn.pilinux.workers.dev/images/App.Dev.Academy/Flutter.Apps/multiple_screens/Home.png
[02]: https://cdn.pilinux.workers.dev/images/App.Dev.Academy/Flutter.Apps/multiple_screens/AboutUs.png
[03]: https://cdn.pilinux.workers.dev/images/App.Dev.Academy/Flutter.Apps/multiple_screens/Contact.png
