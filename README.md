# MBE-modified-csl
A modified .csl file that includes formatting for bioRxiv preprints. 
This CSL file was verified, per Zotero's recommendation: https://validator.citationstyles.org/

Modified for integration with Zotero, not tested on other citation managers. 
Link to discussion on Zotero forums: https://forums.zotero.org/discussion/110771/preprint-formatting-for-molecular-biology-evolution

The modification includes an added "preprint" macro, which pulls from Zotero's "Repository" field. The repository field is mapped to the "publisher" variable in CSL.  
Useful tables that show how Zotero item types map to CSL: https://aurimasv.github.io/z2csl/typeMap.xml
<code> 
<macro name="preprint">
    <group delimiter=" " prefix=" " suffix=".">
      <text variable="publisher" font-style="italic"/>
    </group>
</code> 

This .csl file will add bioRxiv in italics after the the title of the preprint, followed by the URL of the preprint. 
