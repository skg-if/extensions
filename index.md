---
title: SKG-IF Extensions
layout: default
nav_order: 6
---

# Extensions

{: .highlight }
**In a nutshell**: Extensions primarily act as plug-ins for extra properties that enhance the core entities defined by the SKG-IF, for extra entities capturing community concepts, and for relationships between properties.

Introducing extensions to the SKG-IF serves as a strategic step towards addressing the evolving and diverse needs of scientific communities and projects.
The concept of extensions within the SKG-IF is designed to cater to shared interests and requirements that the existing standard entities and properties may not fully meet.

By allowing for the development of extensions that enrich the core model entities of the SKG-IF, the framework can accommodate specialised use cases, specific research needs, and emerging data requirements without compromising the integrity and structure of the core framework. 
Extensions offer a way to further develop the framework's capabilities without disrupting existing entities, maintaining compatibility, coherence, and interoperability across diverse datasets and knowledge graphs.


## Participation guidelines
These are the engagement rules that proponents of a new SKG-IF extension should follow in order to be eligible:
- **Shared Interest/Need:** Extensions should address a collective interest or requirement identified within projects, communities, or domains rather than catering to individual or isolated needs. This principle ensures that extensions serve a broader purpose and contribute to the overall advancement of scientific knowledge representation.
- **Non-Interference:** Extensions should not interfere with or disrupt the entities and APIs already defined within the SKG-IF or other endorsed extensions. They should not serve as shortcuts for sharing information that should be placed elsewhere within the framework. By adhering to this principle, the integrity and coherence of the SKG-IF are preserved.


## Scope of an extension
An SKG-IF extension can cover three distinct aspects about the data model:
- **Core entity extensions:** new properties and relation that extend the set of propertiesand relations of core entities to address the needs of the specific case statement;
- **Brand-new additions:** brand-new entities that reflect semantics and structure different from the core entities, i.e., no core entity can be seen as a super-entity of community entities.

Furthermore, an extension can provide **additional specifications for the APIs**, more specifically:
- Define a list and the relative behaviour of **additional HTTP parameters** to customise the behaviour of the [core API resolver methods]({% link api/index.md %}) defined by the SKG-IF;
- Define **brand-new, additional API methods** with advanced functionalities and custom behaviours.


## Applying for an extension
In order to apply for an SKG-IF extension, proponents should head to the [SKG-IF extensions repository](https://github.com/skg-if/extensions) on GitHub, and open a **new issue** by selecting the proper template and follow the prompted instructions.
For the sake of simplicity, the following [**link**](https://github.com/skg-if/extensions/issues/new?assignees=&labels=new+extension&projects=&template=new-skg-if-extension.md&title=) can be used.

Please note that:
- All the fields between angle brackets included in the aforementioned template must be substituted with the appropriate text. 
- All the fields are mandatory unless specified otherwise.
- Requests will be evaluated by the members of the RDA WG on the SKG-IF. 
- It is possible for a new proposal to have a few iterative responses before being given a final response on whether or not the proposed ontology is endorsed. 

Once the extension is accepted, a new repository will be created, and proponents should work on that codebase following the suggested folder structure.


## Documenting an extension
Comprehensive online documentation for extensions is essential, stating the targeted SKG-IF version(s), the entities they enrich, any new entities introduced, and a detailed description of properties.
This documentation ensures clarity, transparency, and consistency in the development and implementation of extensions.
Once a new extension reaches the expected level of maturity, it will be listed at the bottom of this page and in the navigation bar on the left-side of the page.

{: .important }
In order to prevent clashing with other extensions, an extension should specify an agreed namespace to be used as a prefix for introduced entities, properties, relations and API specifications (i.e., methods and HTTP parameters).


## Extension lifecycle
The lifecycle (i.e., development and maintenance) of an SKG-IF extension falls outside the scope of the RDA WG and the discussion around the core model. 
Therefore, delivering an extension can be fast-paced as long as it meets the expected degree of clearness and compliance. 
Once an extension is mature enough and has been adopted in the intended contexts, part of the covered aspects can be considered and cherry-picked by the WG for inclusion in the SKG-IF core model.
