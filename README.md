[![Build status](https://ci.appveyor.com/api/projects/status/lv6ptih8d46bkj49?svg=true)](https://ci.appveyor.com/project/klacol/bim-profiles)

## What are BIM Profiles?

A BIM profile is a digital template for the information request of a BIM application, comparable to an structured form. For a successful exchange of information, the sender and recipient of the information must agree on a BIM profile for their purpose in advance.

BIM profiles can be agreed as the contractual basis for the information deliveries from service performances. They are sort of a digital expression for Information Exchange Requests.

## Which information can be stored in a BIM Profile?

A BIM profile contains a maximum of five classifications (min. one). Each classification has one of these types, whereby a type may occur only once in a profile:
* Classification of Space Usage Types (e.g. from DIN 277-2, ISO 81346-2-Table 4)
* Classification of Object types (e.g. from CAFM-Connect, Omniclass, Uniclass, COBie)
* Classification of Document types (e.g. from GEFMA 198, GEFMA 924.60)
* Classification of Building Types (e.g. from GEFMA 924.10)
* Classification of Cost Groups (e.g. from DIN 276)

In addition, the profile can contain class related properties for master data, running data, BIM, maintenance, servicing, energy data, etc.

## In which format is the profile stored?

The BIM Profiles are expressed as an IFC file (IFC4 final), either in the file type *.ifcXML or in the file typ *.ifc.

The BIM Profiles are stored as an open library, and these libraries can be read by the BIM applications, like CAFM-Connect-Editor, Archicad, Allplan, Revit, BIMQ, if these application support the import of open libraries.

## This repository
This repos provides the [source of the BIM Profiles](https://github.com/CAFM-Connect/BIM-Profiles/tree/master/ProfileFiles). The BIM profiles are also online available here

https://www.cafm-connect.org/bim-profile
