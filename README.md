# lipidontology.com
LION/web | Lipid Ontology enrichment analysis

## change log:

###### 2019-10-15:
* LION/web: improvement of two-sided KS-test
  * information about down- or upregulation of LION-terms is now available in an extra column
  * enrichment graph can be grouped by down- vs. upregulation

###### 2019-10-10:
* LION/web: improvement of function 'smart matching'
  * unmatched lipids are linked to applicable related terms higher in the hierachy: summed-FA lipids, fatty acids, (sub)classes
* LION/web: input lipids are given an unique ID (#0001, #0002, etc.)
  * if lipid species are provided more than once, they are now treated as separate features
* LION: addition of terms representing sphingolipid backbones other than d18:0 and d18:1
  * d20:0, d20:1, t20:1, etc.
  * Check the full list in '20191010 Added LION-terms.csv'

###### 2019-10-01:
* LION/web: improved support to download enrichment network
  * zip-file now contains: 
    * PNG- and SVG-image of the network
    * RData- and R-file for user-customization 

###### 2019-09-16:
* LION/web: addition of new function 'smartmatching'
  * when switched on, LION/web checks if unmatched lipid species can be associated with parental terms

###### 2019-08-07:
* LION: rewiring of terms related to fatty acid unsaturation.
  * 'fatty acid with more than 3 double bonds' (LION:0002976) is now a child-term of 'polyunsaturated fatty acid' (LION:0002967)

###### 2019-07-04:
* LION: addition of odd numbered fatty acids and links to new lipid species (+43672 terms)
  * Check the full list in '20190704 Added LION-terms.csv'

###### 2019-07-09:
* LION/web: support of LipidXplorer lipid formatting
* LION/web: addition of downloadbutton to download network as SVG

