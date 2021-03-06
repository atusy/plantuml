
# plantuml 0.2.3.1

## Change in default behaviour
* added "-Djava.awt.headless=true -splash:no" as default java_opt to keep java quiet

## Minor changes
* add argumwent *beta* to function updatePlantumlJar() to enable download from beta versions
* added check if plantuml.jar has been downloaded - will download it automatically when not downloaded

## Diverse
* add GPL 3 License
* add DOI to Readme

# plantuml 0.2.3
* quote names of objects to avoid errors with non-text-characters

# plantuml 0.2.2.3
* add java_opt argument to plot.plantuml() to allow additional java arguments. Thanks samssann in https://github.com/rkrug/plantuml/issues/1
* add factor support
* Fix wrong itteration through attributes which resulted in only the first attribute being shown
* Fixes in Documentation

* CHANGES:
* Generate class diagram instead of object diagram - nicer to see tattriburtes and contains.

# plantuml 0.2.2.1
version bump

# plantuml 0.2.2.1
* fixed error when object has more than one class

# plantuml 0.2.2.1
* add BasicUsage vignette
* fix du=ocumentation errors

# plantuml 0.2.2
* fix wrong version

# plantuml 0.2.1
* revert back to using `.eps` as intermediate format instead odf `.svg`
* Added asp = 1 to `plot::plantuml()` to always plot the `.eps` in the correct ratio.

# plantuml 0.2.0

* Added a `NEWS.md` file to track changes to the package.

* Added vector format as intermediate format for plotting to device, used as defasult now.

