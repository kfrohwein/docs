[index]: https://github.com/massiveart/sulu-docs/tree/master/system-requirements/ "Index"
[label_100]: https://github.com/massiveart/sulu-docs/tree/master/system-requirements/100-basic "100 Basic"
[package_1100]: https://github.com/massiveart/sulu-docs/tree/master/system-requirements/100-basic/caching.md "1100 Caching Mechanisms"
[package_1150]: https://github.com/massiveart/sulu-docs/tree/master/system-requirements/100-basic/url-management.md "1150 URL Management"
[package_1200]: https://github.com/massiveart/sulu-docs/tree/master/system-requirements/100-basic/structure.md "1200 Content Structure"
[package_1250]: https://github.com/massiveart/sulu-docs/tree/master/system-requirements/100-basic/multi-portal.md "1250 Multi-portal Capability"
[package_1300]: https://github.com/massiveart/sulu-docs/tree/master/system-requirements/100-basic/multi-lingual.md "1300 Multi-lingual Capability"
[package_1350]: https://github.com/massiveart/sulu-docs/tree/master/system-requirements/100-basic/workflow.md "1350 Workflow Management"
[package_1400]: https://github.com/massiveart/sulu-docs/tree/master/system-requirements/100-basic/publication.md "1400 Publication"
[package_1450]: https://github.com/massiveart/sulu-docs/tree/master/system-requirements/100-basic/sem-seo.md "1450 SEM/SEO Support"
[package_1500]: https://github.com/massiveart/sulu-docs/tree/master/system-requirements/100-basic/search "1500 Search"
[package_1550]: https://github.com/massiveart/sulu-docs/tree/master/system-requirements/100-basic/interfaces "1550 Data Interfaces"
[package_1600]: https://github.com/massiveart/sulu-docs/tree/master/system-requirements/100-basic/security "1600 Security"
[package_1650]: https://github.com/massiveart/sulu-docs/tree/master/system-requirements/100-basic/image-handling "1650 Image Handling"
[label_200]: https://github.com/massiveart/sulu-docs/tree/master/system-requirements/200-settings "200 Settings"
[label_300]: https://github.com/massiveart/sulu-docs/tree/master/system-requirements/300-portals "300 Portals"
[package_3500]: https://github.com/massiveart/sulu-docs/tree/master/system-requirements/300-portals/forms.md "3500 Forms"
[label_400]: https://github.com/massiveart/sulu-docs/tree/master/system-requirements/400-assets "400 Assets"
[label_500]: https://github.com/massiveart/sulu-docs/tree/master/system-requirements/500-contacts "500 Contacts"
[label_600]: https://github.com/massiveart/sulu-docs/tree/master/system-requirements/600-global "600 Global"
[label_700]: https://github.com/massiveart/sulu-docs/tree/master/system-requirements/700-dashboard "700 Dashboard"

> [100 Basic][label_100]

###1300 Multi-lingual Capability
####FR-1301 IP to Location
The IP-to-location function automatically forwards the user to the language version of his country of origin. Sulu has to support an IP-to-location service, implemented as a plugin. The mapping of the country-specific IP-address ranges to the different languages can be done by system engineers. A user interface for content managers has do be planned for later versions.  
####FR-1302 Language fall back
The user must be able to choose a different language for a site or a content area within the specific language version of a portal. All sites within a content node has to be viewable as a list showing all available languages and the assigned language. The language fall back function has also be accessible over the list view. 
####FR-1303 Copying a language version
…accessible over the list view!