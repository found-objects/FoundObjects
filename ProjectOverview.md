# Found-Objects

From FabLabs and makerspaces to commercial production facilities, digital fabrication tools such as CNC routers provide a dynamic way to produce highly-custom objects and components with few restrictions in shape or form. However, this freedom also generates waste. With Found Objects, we aim to reduce this waste using software that can recognize and create functional components from left-over sheet-material before production begins. We have now designed interior elements based on this process, but see most potential in opening the process to others: inviting more production-facilities to use the process and open collaborations with artists / designers developing new possibilities and outcomes.

​

​

Found Objects is a collaboration between Fiction Factory, Jesse Howard, and IAAC. 

Our Team consists of:

Marije Remigius \(Fiction Factory\)
Vincent Mesker \(Fiction Factory\)
Alexandre Dubor \(IAAC\)
Vincent Huygue \(IAAC\)
Ardeshir Talei \(IAAC\)
and
Jesse Howard

​

This project has received funding from the European Union’s Horizon 2020 research and innovation programme under grant agreement 951813.

## Backstory



Fiction Factory is a company based in Amsterdam which produces custom made B2B interiors from a diverse range of materials. For the past three years, Fiction Factory has focused on production with circular engineering principles. However, even with these principles in place, the production they execute also creates a lot of waste. At Fiction Factory 78% of this waste is wood, and most of this wood waste is created by digital production on their CNC machines.

​

![image](https://wikifactory.com/files/RmlsZTo3Mjg2NTA=)

```
CNC Woodwaste at Fiction Factory
```

​

Like many other production facilities, the use of CNC routers at Fiction Factory allows for the production of highly custom interiors with fast turnaround times. However, because the types of projects and engineered parts are constantly changing, it is not possible to fully optimize the material use. In general, an average of 30% of sheet material processed by CNC ends up as waste. For Fiction Factory, this means that they throw away an equivalent of 2000 sheets of new material every year. To prevent this type of waste Fiction Factory has been working in collaboration with IAAC on open source hardware and software solutions for the left over space on their sheets - including implementation of a new cnc workflow.



## Software



In a continued quest to reduce waste and use more of each sheet of material, Fiction Factory collaborated with IAAC and Jesse Howard to create new open source software solutions. By anticipating that each sheet of material will contain leftover space, we developed tools that allow new usable components to be automatically generated from this space.

​
[![growing parts in CNC waste](https://img.youtube.com/vi/14kSnQ6gd3Q/0.jpg)](https://www.youtube.com/watch?v=14kSnQ6gd3Q)

​

This tool is based on the CAD software Rhinoceros and Grasshopper. Though these are commercial proprietary software packages, they are also very widely used. By developing open-source scripts and plugins for the software, we hope to create more possibilities for applying the solutions on many more CNC machines all around the world. Our hope is that the process of ‘“finding” components based on leftover material can happen on a distributed scale, and that new objects will arise based on specific local conditions.



## Process


Currently, the process of creating a ”found object” can be simplified as follows:

1.     Designed components to be produced are nested on a sheet of material.

2.     Grasshopper programs are applied which identify leftover space on the sheet and generate components.

3.     These components then become the material for newly designed objects.

​

![image](https://wikifactory.com/files/RmlsZTo3Mjg2NzE=)


## Objects



At this moment we have produced a few objects that exhibit this process and show possibilities for types of objects that can be created from the generated left-over components: a shelving unit, a stool, and a wall-cladding system.

​

![image](https://wikifactory.com/files/RmlsZTo3Mjg2NTQ=)

```
Found Objects: sample components, panel from wall cladding system, shelf and stool
```

​

The objects show different strategies for working with leftover space: either creating components directly based on the profile of the parts originally cut from the sheet, or, in the case of the wall cladding system, utilizing genetic algorithms to dynamically create organic forms which fit within leftover space on the sheet.

​

![image](https://wikifactory.com/files/RmlsZTo3Mjg2NjA=)

```
Details: components close to original leftover space or organically generated 
```

​

﻿

Ideally, we see these objects and the digital tools they are based on as a taking-off point for CNC operators to apply toward reducing waste, and for other designers to create new typologies of “Found Objects”.



## Nesting



To explain the process in an analog way,  and show the problem of the nesting components for CNC production, we have created the Better CNC Factory Nesting game. A product of its own in which players take on the role of the nesting software, and compare their own speed and efficiency with Fiction Factory’s own nesting expert Vincent Mesker.

​
[![CNC Nesting Game](https://img.youtube.com/vi/Y7UNH0xUYU4/0.jpg)](https://www.youtube.com/watch?v=Y7UNH0xUYU4)


## Vision



Fiction Factory aims to connect with Makerspaces, FabLabs and SMEs to engage a community of creatives, practitioners and potential customers in new processes of considering waste as part of the design and production process. We aim to co-create new open source products. Our research aims to find a way to make open source hardware \(OSH\) a viable business option, as well as encourage people and businesses alike to find and contribute open alternatives to existing business models.
