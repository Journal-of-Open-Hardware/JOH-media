# Review of OSH documentation guidelines

This document describes the requirements for hardware documentation implied by the [Open Source Hardware (OSHW) Statement of Principles 1.0](https://www.oshwa.org/definition/), which states that “open source hardware is hardware whose design is made publicly available so that anyone can study, modify, distribute, make, and sell the design or hardware based on that design.” According to this definition, a physical product qualifies for the designation Open Source Hardware when its documentation grants anyone with the four freedoms of open source: freedom to study, modify, make, and distribute. This document gives an overview of the documentation features making these freedoms effective.

*Note: Making a hardware product open source is often used as a way to gather a community of people contributing to the design. Using open source as a product development model implies additional requirements for documentation. However, since the aspect of participative development is not explicitely covered by the Open Source Hardware Definition, the corresponding additional requirements are not considered here.*

## Taxonomy of OSH documentation contents

* Contextual information
  * Product description
  * Functionalities and applications
  * Versionning history (current version and change log)
  * Current state of development and liability issues
  * Known issues
  * Author identification
* Dependencies with other software or hardware products, especially proprietary ones
* Bill of materials, indicating for each part
  * Name of the part
  * Reference designation (e.g. part number in the nomenclature)
  * Photo or illustration
  * Exact specifications
  * Quantity
  * Procurement information
  * Cost
  * Reference of the corresponding design file
* Design files
   * Description of the design rationale and product architecture
   * Electronics schematics
   * Circuit board layouts
   * Mechanical CAD models, assemblies
   * Simulation files
   * Software source code
* Fabrication instructions
   * Step by step assembly instructions, including safety warnings
   * Part fabrication details (e.g. Materials, machine parameters)
   * Production files (e.g. Gcode, STL, CAD drawings)
* Calibration and testing procedures
* OSH-compatible license, including
  * credits
  * compatibility issues

## OSH documentation characteristics

* **Targeted**: it specifies a clear target audience, as a prerequisite to ensure appropriate accessibility and sufficiency of information (see next two points).

* **Accessible** in terms of:
  * **language**: it is structured in a comprehensible manner and written in a language which is clearly understandable by the targeted audience. For example, in case this audience is the general public, this means writing in a jargon-free language without sacrificing technical detail, generously supported by illustrations.
  * **file format**: the documentation is enclosed in formats which can commonly be read by the targeted audience. Talking about computer file formats, this means that information is stored in file formats which can be opened with the software equipment the targeted audience can be reasonably expected to have access to. For example, if the targeted audience is the general public, this criteria requires providing information in file formats which can be opened with inexpensive and commonplace software products.

* **Sufficient**: it includes all information required by the targeted audience to study, modify and make the product. That is, all information they require to understand the hardware design and to replicate it.

* **Findable**: it is located in locations that a user would expect. Examples: in a public repository linked to from community webpages, in open access journals, under an URL given in the product packaging.

* **Without condition**: access is granted to the documentation without any condition and is not protected under any paywall or registration system (no discrimination against persons or groups).

## Time perspective

* Providing a documentation is a prerequisite for qualifying for the designation Open Source Hardware. Consequently, a product can be called open source only ++after++ its documentatin has been made available.

## How to cheat it

All these requirements are a question of fair measure. If you don't like to be fair and want to play it dirty, this is how to do it:
* Write your documentation for a very specific target audience that nobody qualifies for. Like, mechanical engineers reading ancient greek fluently.
* Who cares about documentation strucutre: just put all files in a flat directory, name the files randomly, especially those which are linked with each other (like CAD assemblies).
* Release only parts of the documentation. No one will argue if you forget a few files, even of they are critical. I mean, it's already nice from you that you shared already some files.
* Instead of putting the documentation direct online, just provide a contact form where people can put their email to recieve the download link in their inbox. And never send the mail.
* Use broken URLs, a very efficient way to give the impression you really wanted to share the files, but well you know, the sever went down and bla bla bla...
* Put the documentation online, but make it very difficult to find the link. That way, you will always be able to justify you have published the docs if you are explicitely asked to but no one will find them by themselves.
* Use wierd files formats no one use. The best ones are those you may develop by yourself. In those cases, of course, do not share the format definition.
* Provide file formats no one can do anything with. Instead sharing a CAD model in its original format, make a 3D-PDF of it. The only thing people will be able to do with is to display it on their screen.
* Provide dry documentation, only drawings, no text. Descriptions are for the weak.
* 

Of course this paragraph is not trying to encourage you to play dirty. We know you are a virtuous person with high ideals. But these are the grey zones of Open Soure Hardware.