Dokuwiki Plugin: Add New Page
=============================

The add new page plugin for Dokuwiki: https://www.dokuwiki.org/plugin:addnewpage

This is free software, released under the [GPL version 2](https://www.gnu.org/licenses/gpl-2.0-standalone.html).

## Syntax

    {{NEWPAGE[>namespace]}}

	{{NEWPAGE|Title}}
	
    {{NEWPAGE>your:namespace}}
	
    {{NEWPAGE|Title>your:namespace}}
	
    {{NEWPAGE#newtpl1,newtpl2}}
	
    {{NEWPAGE#newtpl1|Title1,newtpl2|Title1}}
	
    {{NEWPAGE>your:namespace#newtpl1|Title1,newtpl2|Title1}}
	
    {{NEWPAGE|Title>your:namespace#newtpl1|Title1,newtpl2|Title1}}

Where namespace is optional, and indicates the destination namespace for the new page.
If you give @NS@ or @PAGE@ as namespace, the namespace of the current page or the current page ID will be used.

## Authors

- Originally written by [Benjamin Santalucia](https://github.com/ben8p) (aka iDo), 2006.
- Moved to Github by hamstar <hamstar@telescum.co.nz>, 2012.
- Updated by Sam Wilson <sam@samwilson.id.au>, 2013.
- Updated by Michael Braun <michael-dev@fami-braun.de>, 2013.
- Improved by Róbert Toth (FurloSK), 2013.
- Support for newpagetemplate added by Gerrit Uitslag <klapinklapin@gmail.com>, 2014.
- Disabling of restricted parent namespaces by Albert Chern, 2015.
- Added function for a button title by Ralf Kornberger, 2019
