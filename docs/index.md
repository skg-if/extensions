# SKG-IF extensions


## List of supported extensions
TBA


## Rationale
**In a nutshell:** Extensions primarily act as plug-ins for extra properties that enhance the core entities defined by the SKG-IF, for extra entities capturing community concepts, and for relationships between properties.

Introducing extensions to the SKG-IF serves as a strategic step towards addressing the evolving and diverse needs of scientific communities and projects.
The concept of extensions within the SKG-IF framework is designed to cater to shared interests and requirements that the existing standard entities and properties may not fully meet.

By allowing for the development of extensions that enrich the core model entities of the SKG-IF, the framework can accommodate specialised use cases, specific research needs, and emerging data requirements without compromising the integrity and structure of the core framework. 

The justification for incorporating extensions lies in ensuring that the SKG-IF remains flexible, adaptable, and responsive to the changing landscape of scientific knowledge representation. 
Extensions offer a way to further develop the framework's capabilities without disrupting existing entities, maintaining compatibility, coherence, and interoperability across diverse datasets and knowledge graphs.

Furthermore, by mandating online documentation and requiring a case statement for each extension, the framework enhances transparency, visibility, and accountability. 
This approach not only fosters collaboration and knowledge sharing but also encourages innovation and continuous improvement in how scientific knowledge is modelled, shared, and utilised.

In summary, introducing extensions to the SKG-IF framework is a strategic decision to promote inclusivity, community-driven development, and the seamless integration of specialised knowledge representations within a standardised interoperability framework. 
This approach ensures that the SKG-IF remains relevant, robust, and responsive to the evolving needs of scientific research and data management practices.

An extension of the SKG-IF is motivated by the need to address specific requirements, interests, or challenges encountered within a particular scientific community.
The primary motivations for developing an SKG-IF extension include:

- **Tailored Solutions:** SKG-IF extensions allow for the customisation and tailoring of the SKG-IF to meet the unique needs and use cases of a specific scientific community. By incorporating domain-specific entities, properties, or relationships, the extension can enhance the relevance and applicability of the framework within that community.
- **Improved Interoperability:** SKG-IF extensions help foster better interoperability among scientific community members by providing a standardised approach to representing and sharing domain-specific knowledge. This promotes consistency in data modelling and facilitates data exchange and integration within the community.
- **Efficiency and Productivity:** By defining domain-specific entities and properties through an SKG-IF extension, researchers and practitioners within the community can streamline data management processes, improve data discovery, and enhance the overall productivity of knowledge creation and dissemination activities.
- **Knowledge Sharing and Collaboration:** SKG-IF extensions encourage knowledge sharing and collaboration among community members by establishing a common framework for representing and exchanging scientific data and information. This shared understanding facilitates communication and collaboration across diverse research projects and initiatives.
- **Empowerment, Accountability, and Ownership:** Developing an SKG-IF extension empowers scientific community members to actively contribute to the evolution and enhancement of the SKG-IF framework. It fosters a sense of ownership and investment in the standardisation efforts, encouraging community engagement and participation in shaping the future of scientific knowledge representation.


## Participation guidelines
These are the engagement rules that proponents of a new SKG-IF extension should follow in order to be eligible

- **Shared Interest/Need:** Extensions should address a collective interest or requirement identified within projects, communities, or domains rather than catering to individual or isolated needs. This principle ensures that extensions serve a broader purpose and contribute to the overall advancement of scientific knowledge representation.
- **Non-Interference:** Extensions should not interfere with or disrupt the entities already defined within the SKG-IF. They should not serve as shortcuts for sharing information that should be placed elsewhere within the framework. By adhering to this principle, the integrity and coherence of the SKG-IF are preserved.

## Applying for an extension
In order to apply for an SKG-IF extensions, proponents should head to the [SKG-IF extensions repository](https://github.com/skg-if/extensions) on GitHub, and open a **new issue** selecting the proper template and follow the prompted instructions.
For the sake of simplicity, the following [**link**](https://github.com/skg-if/extensions/issues/new?assignees=&labels=new+extension&projects=&template=new-skg-if-extension.md&title=) can be used.
Please note that:
- All the fields between angle brackets included in the aforementioned template must be substituted with the appropriate text. 
- All the fields are mandatory.

Requests will be evaluated by the members of the RDA WG on the SKG-IF. 
It is possible for a new proposal to have a few iterative responses before being given a final response on whether or not the proposed ontology is endorsed. 


## Documenting an extension
Comprehensive online documentation for extensions is essential, stating the targeted SKG-IF version(s), the entities they enrich, any new entities introduced, and a detailed description of properties.
This documentation ensures clarity, transparency, and consistency in the development and implementation of extensions.
Extensions are published via the SKG-IF documentation site in the dedicated section “Supported extensions”.

The documentation of an SKG-IF extension is structured in three parts:

- **Extension-specific entities:** brand-new entities that reflect semantics and structure different from the core entities, i.e. no core entity can be seen as a super-entity of community entities;
- **Core entity extensions:** properties that extend the set of properties of core entities to address the needs of the specific case statement;
- **Extension-specific relationships:** relationships that link entities (either core or extension-specific) reflecting the semantics of the case statement.
