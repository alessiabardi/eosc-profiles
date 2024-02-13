.. EOSC - PROFILE documentation master file, created by
   sphinx-quickstart on Tue Sep  6 11:28:53 2022.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to EOSC - PROFILE Specifications
=======================================

Introduction
------------

EOSC Profiles are metadata schemas for the description of services, research products or other research artefacts that their providers choose to share with the EOSC user community through the EOSC Exchange, as well as for describing the organisations offering to provide these resources to EOSC.  Any provider or other responsible party (the “Provider” or the “Catalogue Operator”) that intends to include one or more research resources (“resources”) in EOSC must describe each resource using the appropriate EOSC Profile, with Profile records for both themselves and those resources in the machine-readable digital formats specified here.  Once described, the Provider or Catalogue Operator submits EOSC Profile records to the EOSC COre Platform for processing following the applicable procedures for onboarding.  If the processing is successful, the subject of each approved EOSC Profile record will be listed, findable and accessible in the EOSC Marketplace and can be integrated with other EOSC Core Services, pursuant to the respective EOSC Interoperability Guideliness for those services. In this way EOSC Profiles ensure findability of information about any entity or resource within the system-of-systems framework of EOSC.

These Github specifications of the EOSC Profile schemas, and their role in supporting the onboarding of resources to EOSC, are more completely described in the following document: <https://zenodo.org/records/10621226>

EOSC Profiles have several functions:

* **Onboarding to EOSC**: EOSC Profile records include information needed to assess the compliance of a specific Provider, Catalogue Operator and/or Resource with the Rules of Participation of EOSC, as well as the specific Inclusion Criteria used by those responsible for onboarding such entities into the EOSC Exchange and monitoring their continued compliance with the Rules of Participation.
* **Search, Display and Filter within EOSC**: EOSC Profile records include information needed to include the Provider and/or Resource in the EOSC Resource Catalogue (combining the EOSC Service Catalogue and EOSC Research Product Catalogue) and the EOSC Marketplace. Generally, a Provider or Resource is included (displayed) automatically in the EOSC Marketplace once it has been included in the EOSC Resource Catalogue.  
* **Integration with EOSC Core Services**: EOSC Profile records act as reference identifiers to support integration of any Resource with one or more EOSC Core Services, including EOSC Monitoring, EOSC Accounting, EOSC Helpdesk and EOSC Order Management.  Specific integrations are detailed in various “extensions”, which are themselves described in the relevant Interoperability Guideline (IG) for the EOSC Core Service that uses an extension (see Section 7: Related Guidelines).  Extensions are not part of the EOSC Profile schema, but refer to the identifier of the corresponding EOSC Profile record.  (Note that, in the abstract, function 2 above represents integration of a resource with the EOSC Resource Catalogue and the EOSC Marketplace, both of which are Core Services  – but no specific “extension” is required for this, and this integration is the implicit purpose of the EOSC Profile itself.)
* **Anchoring of capabilities in EOSC**: Certain EOSC Profiles enable a range of possible resources to be described, and specific Subprofiles are defined to enhance the three functions described above for a specific type of resource.  At the time of writing, one Subprofile schema , for a Data Source, has been defined, enhancing the generic Service Profile schema.  This Subprofile schema is documented below.  Other subprofiles are planned for future implementation, particularly for Services that describe computational resources, and for Services that describe data storage resources.

Version 5.0 of the EOSC profile schemas was created during the implementation of the EOSC Future project and reflects the architectural concepts based on the community inputs and expertise of the project partners at the time of implementation. It accumulates numerous changes in the profiles itself, and in the procedures for gathering the community input that have been agreed-upon by a wide group of stakeholders. EOSC concepts as well as the EOSC community have been experiencing rapid evolution during the last months of the EOSC Future project. Accumulation of the new demand and subsequent implementation of new versions of EOSC Profile schemas will have to be undertaken after the EOSC Future project finishes on 31 March 2024.


Profile overview
================

* `EOSC Provider Profile <https://eosc-provider-profile.readthedocs.io/>`_
* `EOSC Service Profile <https://eosc-service-profile.readthedocs.io/>`_
* `EOSC Multi-Provider Catalogue Profile <https://eosc-catalogue-profile.readthedocs.io/>`_
* `EOSC Interoperability Guideline Profile <https://eosc-interoperability-profile.readthedocs.io/>`_
* `EOSC Training Profile <https://eosc-training-profile.readthedocs.io/>`_

`Link to Human Readable Version of this Page (ReadtheDocs): <https://eosc-profiles.readthedocs.io/en/latest/>`_
