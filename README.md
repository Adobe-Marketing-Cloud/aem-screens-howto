Screens HowTo project
=====================

The Screens HowTo project is a sandbox for demoing the full spectrum of capabilities of AEM Screens in the context of the AEM platform.
It focuses on customer use-cases that can be covered with out-of-the-box features or minimal development, and that go beyond the simple image slideshow to integrate for the rest of the platform features.

The audience for this project is mainly product managers, solutions consultants and sales teams.

Getting started
---------------

- Download the [last release](../../releases/latest)
- Install the content package in AEM using the [Package Manager](http://localhost:4502/crx/packmgr/index.jsp) accessible through Tools &rarr; Deployment &rarr; Packages
- Go through the [use cases](#use-cases)

### Compatibility

The Screens HowTo project is meant to work on the latest Screens feature packs on AEM 6.3 and 6.4. Based on differences in the feature sets of each AEM version, some use cases will have some additional compatibility information. Just refer to the respective README for more details.

AEM|Screens FP|Compatibility
-|-|-
6.4.2|[Screens FP2](https://www.adobeaemcloud.com/content/marketplace/marketplaceProxy.html?packagePath=/content/companies/public/adobe/packages/cq640/product/screens/cq-6.4.0-featurepack-screens)|:white_check_mark:
6.3.3|[Screens FP4](https://www.adobeaemcloud.com/content/marketplace/marketplaceProxy.html?packagePath=/content/companies/public/adobe/packages/cq630/featurepack/cq-6.3.0-featurepack-screens)|:white_check_mark:

Use Cases
---------

Name|Description
-|-
[accuweather](usecases/accuweather/)|Dynamic content based on live weather information
[asciicodes](usecases/asciicodes/)|Dynamic content based on keyboard input
[damdrivenfolder](usecases/damdrivenfolder/)|Authoring the content of the Screens channels directly from _AEM Assets_ folder using a non-editable sequence
[damdriventags](usecases/damdriventags/)|Authoring the content of the Screens channels directly from _AEM Assets_ tags. A different take on the DAM-driver approach with a non-editable channel instead of a non-editable sequence
[experiencefragments](usecases/experiencefragments/)|Reuse _Experience Fragments_ coming from AEM Sites directly in the Screens channels
[languagecopies](usecases/languagecopies/)|Automatic channel content translation leveraging _AEM Sites Translation Cloud Services_
[launches](usecases/launches/)|Scheduled content rollout leveraging _AEM Sites Launches_
[livecopies](usecases/livecopies/)|Branch-specific content variations leveraging _AEM Sites Live Copies_
[multizoneeditor](usecases/multizoneeditor/)|Multi-zone channel editor that allows custom layouts by leveraging _AEM Responsive Layout_
[specialevents](usecases/specialevents/)|Branch-specific scheduled content overrides for special events using day-parting and channel priorities
[statichtmlcontent](usecases/statichtmlcontent/)|Importing external HTML/JS/CSS experiences directly in your channel (for instance _Animate CC_ experiences)
[subsequences](usecases/subsequences/)|Branch-specific content variations leveraging _Screens Embedded Sequences_
[datatriggers](usecases/datatriggers/)|Channel switch based on an external event.

Contributing
------------

See [CONTRIBUTING.md](CONTRIBUTING.md) and also take a look at the [adding new use-cases](../../wiki/Adding-new-use-cases) wiki page for the project.


# Entry points

+ Content
    + [HowTo project in DCC](http://localhost:4502/screens.html/content/screens/screens-howto)
+ ContextHub (access: Tools > Sites > ContextHub > screens-howto > ContextHub Configuration)
    + [Stores](http://localhost:4502/etc/cloudsettings/screens-howto/contexthub.html)
    + [Modules](http://localhost:4502/etc/cloudsettings/screens-howto/contexthub/ui.html)
+ Personalization
    + [HowTo Activities](http://localhost:4502/libs/cq/tagging/gui/content/tags.html/etc/tags/screens-howto) (access: Navigation > Personalization > Activities)
    + [HowTo Audiences](http://localhost:4502/libs/cq/personalization/touch-ui/content/audiences.html) (access: Navigation > Personalization > Audiences)
+ Tags
    + [HowTo Tags](http://localhost:4502/libs/cq/tagging/gui/content/tags.html/etc/tags/screens-howto) (access: Tools > General > Tagging)
