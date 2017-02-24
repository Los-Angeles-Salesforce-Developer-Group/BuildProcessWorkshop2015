# BuildProcessWorkshop2015
Sample code and other artifacts for the May 18, 2015 meetup of the Los Angeles Salesforce Developer Group

Recording of the meeting [here] (https://www.youtube.com/watch?v=xhhVIb285U8)

## Agenda
- 6:00pm - Doors open
- 6:15pm - Welcome/Introduction (Nathan Pepper)
- 6:30pm - Continuous Delivery of Success - How the Salesforce platform enables organizations to continuously adapt to change (Alex Sutherland)
- 7:10pm - Automating Pull Request Testing Using Ant and Travis (Daniel Hoechst) -- Slide deck [here](http://www.slideshare.net/dhoechst/team-development-on-forcecom)  GitHub repo [here](https://github.com/dhoechst/Team-Dev-Force-Dot-Com)
- 7:50pm - Continuous Integration of JavaScript and Apex code using Jasmine, PhantomJS, and drone.io (Kevin Poorman)
-- Slide deck [here](http://www.slideshare.net/KevinPoorman1/ci-of-js-and-apex-using-jasmine-phantom-js-and-drone-io-df14)
- 8:30pm - Intro to git, ant, and ivy for Salesforce developers (Nathan Pepper)

If you have Windows, I would strongly recommend installing Cygwin:
http://cygwin.com/install.html

To easily install and update other tools, install [Homebrew](http://brew.sh/) (Mac) or [Chocolatey](https://chocolatey.org/) (Win)

## Getting git
http://git-scm.com/downloads

    brew install git
    or
    choco install git

## Getting make
??? (You should have it already if you are running *nix/MacOSX or Cygwin on Windows)

## Getting ant
* [Binary distributions](http://ant.apache.org/bindownload.cgi)
* [Source distributions (build it!!!)](http://ant.apache.org/srcdownload.cgi)
```
brew install ant
or
choco install ant
```
## Getting ivy
[Apache Ivy - Download (try building it from source!!!)](http://ant.apache.org/ivy/download.cgi)

    brew install ivy
