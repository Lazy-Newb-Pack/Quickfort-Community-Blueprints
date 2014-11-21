Quickfort-Community-Blueprints
==============================

This is a modified version of the [Quickfort Community Blueprints v2.2]( http://dwarffortresswiki.org/index.php/Quickfort_Community_Blueprints), to download the un-edited and orginal version of the [Quickfort Community Blueprints v2.2 click here.](http://www.mediafire.com/download/2x40cv93i9gd1r0/Community_Quickfort_Blueprints_v2.2.zip)

==Previous Blueprint Repositories==

[http://www.mediafire.com/download/2x40cv93i9gd1r0/Community_Quickfort_Blueprints_v2.2.zip The latest (v2.2) collated pack]

[http://www.mediafire.com/download/5fp46epm3fe1z8b/Community_Quickfort_Blueprints_v2.1.zip (v2.1) collated pack]

[https://www.mediafire.com/folder/u38qsqr1bq6wu/Community_Quickfort_Blueprints_v2 (v2.0) collated pack, unzipped], and a [http://www.mediafire.com/download/n6im1ok6z02n8nc/Community_Quickfort_Blueprints_v2.zip zipped version of it] (otherwise requires paid account to download all at once).  

Version one of the collated package is available [http://www.mediafire.com/df_qfcommunity here]. 

The remainder of the page is a set of simple Quickfort-compatible blueprints to give you a sense of what can be done. 

== Circle Pack ==
=== 11-tile circle ===
  #dig start(6;6;Center tile) 11-tile circle
  `,`,`,`,d,d,d,`,`,`,`,#
  `,`,d,d,d,d,d,d,d,`,`,#
  `,d,d,d,d,d,d,d,d,d,`,#
  `,d,d,d,d,d,d,d,d,d,`,#
  d,d,d,d,d,d,d,d,d,d,d,#
  d,d,d,d,d,d,d,d,d,d,d,#
  d,d,d,d,d,d,d,d,d,d,d,#
  `,d,d,d,d,d,d,d,d,d,`,#
  `,d,d,d,d,d,d,d,d,d,`,#
  `,`,d,d,d,d,d,d,d,`,`,#
  `,`,`,`,d,d,d,`,`,`,`,#

=== 13-tile circle ===
  #dig start(7;7;Center tile) 13-tile circle
  `,`,`,`,`,d,d,d,`,`,`,`,`,#
  `,`,`,d,d,d,d,d,d,d,`,`,`,#
  `,`,d,d,d,d,d,d,d,d,d,`,`,#
  `,d,d,d,d,d,d,d,d,d,d,d,`,#
  `,d,d,d,d,d,d,d,d,d,d,d,`,#
  d,d,d,d,d,d,d,d,d,d,d,d,d,#
  d,d,d,d,d,d,d,d,d,d,d,d,d,#
  d,d,d,d,d,d,d,d,d,d,d,d,d,#
  `,d,d,d,d,d,d,d,d,d,d,d,`,#
  `,d,d,d,d,d,d,d,d,d,d,d,`,#
  `,`,d,d,d,d,d,d,d,d,d,`,`,#
  `,`,`,d,d,d,d,d,d,d,`,`,`,#
  `,`,`,`,`,d,d,d,`,`,`,`,`,#

=== 15-tile circle ===
  #dig start(8;8;Center tile) 15-tile circle
  `,`,`,`,`,d,d,d,d,d,`,`,`,`,`,#
  `,`,`,d,d,d,d,d,d,d,d,d,`,`,`,#
  `,`,d,d,d,d,d,d,d,d,d,d,d,`,`,#
  `,d,d,d,d,d,d,d,d,d,d,d,d,d,`,#
  `,d,d,d,d,d,d,d,d,d,d,d,d,d,`,#
  d,d,d,d,d,d,d,d,d,d,d,d,d,d,d,#
  d,d,d,d,d,d,d,d,d,d,d,d,d,d,d,#
  d,d,d,d,d,d,d,d,d,d,d,d,d,d,d,#
  d,d,d,d,d,d,d,d,d,d,d,d,d,d,d,#
  d,d,d,d,d,d,d,d,d,d,d,d,d,d,d,#
  `,d,d,d,d,d,d,d,d,d,d,d,d,d,`,#
  `,d,d,d,d,d,d,d,d,d,d,d,d,d,`,#
  `,`,d,d,d,d,d,d,d,d,d,d,d,`,`,#
  `,`,`,d,d,d,d,d,d,d,d,d,`,`,`,#
  `,`,`,`,`,d,d,d,d,d,`,`,`,`,`,#

== General ==
=== Simple Spiral Staircase ===
  #dig A simple spiral staircase.,,
  j,u,#
  u,j,#
  #>,#,#
  u,j,#
  j,u,#
  #,#,#
=== Slightly larger spiral ===
  #dig A simple spiral staircase.,,
  j,d,u
  d,d,d
  u,d,j
  #>
  u,d,j
  d,d,d
  j,d,u
== Bedrooms ==
=== Modified Windmill Villas ===
This has a central single up/down stair tile that has room for a 3x3 shaft. I don't usually do 3x3. See [[Bedroom Design#Modified Windmill Villas]]
  #dig start(11;11)
  `,`,`,`,`,`,d,`,`,`,`,`,d,`,`,`,`,`,`,`,`,
  `,`,`,`,`,`,d,`,`,`,`,`,d,`,`,`,`,`,`,`,`,
  `,`,`,`,d,`,d,`,d,`,d,`,d,`,d,`,`,`,`,`,`,
  `,`,`,`,d,`,d,`,d,`,d,`,d,`,d,`,`,`,`,`,`,
  `,`,`,`,d,d,d,d,d,`,d,d,d,`,d,`,d,d,d,`,`,
  `,`,`,`,`,`,d,`,`,`,`,`,d,d,`,`,d,`,`,`,`,
  `,`,d,d,d,`,d,`,d,d,d,`,d,d,d,d,d,d,d,d,d,
  `,`,`,`,`,d,d,`,`,`,d,`,d,`,`,`,d,`,`,`,`,
  d,d,d,d,d,d,d,d,d,d,d,d,d,`,d,`,d,d,d,`,`,
  `,`,`,`,d,`,`,`,d,d,d,d,d,`,d,`,`,`,`,`,`,
  `,`,d,d,d,`,d,d,d,d,i,d,d,d,d,`,d,d,d,`,`,
  `,`,`,`,`,`,d,`,d,d,d,d,d,`,`,`,d,`,`,`,`,
  `,`,d,d,d,`,d,`,d,d,d,d,d,d,d,d,d,d,d,d,d,
  `,`,`,`,d,`,`,`,d,`,d,`,`,`,d,d,`,`,`,`,`,
  d,d,d,d,d,d,d,d,d,`,d,d,d,`,d,`,d,d,d,`,`,
  `,`,`,`,d,`,`,d,d,`,`,`,`,`,d,`,`,`,`,`,`,
  `,`,d,d,d,`,d,`,d,d,d,`,d,d,d,d,d,`,`,`,`,
  `,`,`,`,`,`,d,`,d,`,d,`,d,`,d,`,d,`,`,`,`,
  `,`,`,`,`,`,d,`,d,`,d,`,d,`,d,`,d,`,`,`,`,
  `,`,`,`,`,`,`,`,d,`,`,`,`,`,d,`,`,`,`,`,`,
  `,`,`,`,`,`,`,`,d,`,`,`,`,`,d,`,`,`,`,`,`,

===Simple tileable cross design===
It allows ample space for movement and decoration.
  #dig Bedroom complex
  `,`,`,`,`,`,`,`,`,d,d,`,`,`,`,`,`,`,`,`,#
  `,d,d,d,`,d,d,d,`,d,d,`,d,d,d,`,d,d,d,`,#
  `,d,d,d,`,d,d,d,`,d,d,`,d,d,d,`,d,d,d,`,#
  `,`,`,d,`,d,`,`,`,d,d,`,`,`,d,`,d,`,`,`,#
  d,d,d,d,d,d,d,d,d,d,d,d,d,d,d,d,d,d,d,d,#
  `,`,`,d,`,d,`,`,`,d,d,`,`,`,d,`,d,`,`,`,#
  `,d,d,d,`,d,d,d,`,d,d,`,d,d,d,`,d,d,d,`,#
  `,d,d,d,`,d,d,d,`,d,d,`,d,d,d,`,d,d,d,`,#
  `,`,`,`,`,`,`,`,`,d,d,`,`,`,`,`,`,`,`,`,#
  d,d,d,d,d,d,`,`,d,d,d,d,`,`,d,d,d,d,d,d,#
  d,d,d,d,d,d,d,d,d,i,i,d,d,d,d,d,d,d,d,d,#
  d,d,d,d,d,d,d,d,d,i,i,d,d,d,d,d,d,d,d,d,#
  d,d,d,d,d,d,`,`,d,d,d,d,`,`,d,d,d,d,d,d,#
  `,`,`,`,`,`,`,`,`,d,d,`,`,`,`,`,`,`,`,`,#
  `,d,d,d,`,d,d,d,`,d,d,`,d,d,d,`,d,d,d,`,#
  `,d,d,d,`,d,d,d,`,d,d,`,d,d,d,`,d,d,d,`,#
  `,`,`,d,`,d,`,`,`,d,d,`,`,`,d,`,d,`,`,`,#
  d,d,d,d,d,d,d,d,d,d,d,d,d,d,d,d,d,d,d,d,#
  `,`,`,d,`,d,`,`,`,d,d,`,`,`,d,`,d,`,`,`,#
  `,d,d,d,`,d,d,d,`,d,d,`,d,d,d,`,d,d,d,`,#
  `,d,d,d,`,d,d,d,`,d,d,`,d,d,d,`,d,d,d,`,#
  `,`,`,`,`,`,`,`,`,d,d,`,`,`,`,`,`,`,`,`,#
  #,#,#,#,#,#,#,#,#,#,#,#,#,#,#,#,#,#,#,#,#


===11x11 12-room Apartment Block
Features 11 4-tile rooms and one 3-tile room (or it makes a good office), needing only 5 doors. Quite modular.
If you use small meeting locations you can knock out the walls between the two narrow halls for a meeting area surrounded by 10 rooms, which would be very handy if all the rooms were full of families.

  #dig
  d,d,`,d,d,`,d,d,`,d,d,#
  d,d,`,d,d,`,d,d,`,d,d,#
  `,`,d,`,`,`,`,`,d,`,`,#
  d,d,`,d,`,d,`,d,`,d,d,#
  d,d,`,d,`,d,`,d,`,d,d,#
  `,`,`,d,`,d,`,d,`,`,`,#
  d,d,`,d,`,d,`,d,`,d,d,#
  d,d,`,d,`,`,d,d,`,d,d,#
  `,`,d,d,`,d,`,d,d,`,`,#
  d,d,`,d,`,d,`,d,`,d,d,#
  d,d,`,d,`,d,`,d,`,d,d,#
  `,`,`,d,`,`,`,d,`,`,`,#
