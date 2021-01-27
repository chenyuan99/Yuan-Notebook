---
title: Detailed Design
linktitle: Detailed Design
toc: true
type: book
date: "2019-05-05T00:00:00+01:00"
draft: true


# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 3
---

# Detailed Design

- Overview
  - What is detailed design?
  - What is OO design?
  - How should we do OO design?

- Detailed design
  - To decompose subsystems into modules
  - Two approaches of decomposition 
    - Procedual
    - System is decompose
    - Object-oriented
		
- Abstraction
  - To focus on important, inherent properties while suppressing unnecessary details
    - Permits separation of concern
    - Allows postponements
  - Two abstraction mechanisms
    - Procedural abstraction
      - Specification describes input/output
      - Implementation describes algorithm
    - Data abstraction
      - Specification describes attributes, values
      - Implementation describes representation and
manipulation

- OOD
  - To identify responsibilities and assign them to classes and objects
  - Responsibility for doing
    - E.g., create an object, perform calculations, invoking operations on other objects
  Responsibilities for knowing 
		- E.g., attributes, data involved in calculations, parameters when invoking operations
- How Do developers Design Objects?
	- Code
		- Draw, then code
			- UML Diagrams
		- Only draw
			- The tool generates everything from diagrams

- How much time spent drawing UML before coding?
	- Spend a few hours or at most one day (with partners) near 
	- Draw uml for the hard, creative parts of the detailed object design
	- Stop and transition to coding
	- UML drawings
		- Inspiration as a starting point
		- The final design in code may diverge and improve
			
- Detailed design resultes
	- Dynamic models
		- Help design the logic/behavior of the code
		- UML interaction diagrams
	- Static models
		- Help design the definition of packages, class names, attributes, and method signatures
		- (detailed) UML class diagrams
			
- UML Interaction Diagrams
	- To illustrate how objects interact via messages
	- Two types of interaction diagrams
		- Communication diagram 
		- Sequence diagram
			- Illustrate interactions in akind of fence format, in which each new object is added 
				
- How should we do OO Design
	- Responsibility-driven
		
- Responsibilities
	- Obligations/behaviors
		
- Doing Responsibiliities
	- Doing something itself
		
- Guideline
	- The transition of responsibilities into classes and methods is influenced by the gra
		
- Knowing responsibilities
	- Knowing about private encapsulated data
	- Knowing related objects
	- Knowing about things it can derive of calcualate
	  - "a sale of ject"
			
- Guideline
	- The attributes and associations illuatrats=ed by domain objects
	
- GRASP:
	- Principles
		- Creator(doing)
			- Problem: who creates an A?
			- Advice: Assign class B the responsibility to create an instance of class A if:
				- B "contains" or compositely aggregates A
				- Whole-part; assembly
		- Information expert
		- Low coupling
		- Controller
		- High cohesion
		
- Sequence vs communication
- Summary
	- Object fullfill tasks using their info or the info of objects the 
