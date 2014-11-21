# Open Tree of Life reference taxonomy version 2.8

Version 2.8 (also known as version 2.8 draft 5) was generated on 11 June 2014.

## Download

[Download](http://files.opentreeoflife.org/ott/ott2.8.tgz) (gzipped tar file, 119 Mbyte) 

## File format documentation

See [documentation in the reference taxonomy
wiki](https://github.com/OpenTreeOfLife/reference-taxonomy/wiki/Interim-taxonomy-file-format),
on github.

## Build script

The reference taxonomy is an algorithmic combination of several
source taxonomies.  For code,
see <a href="https://github.com/OpenTreeOfLife/reference-taxonomy">the
source code repository</a>.
Version 2.8 was generated using 
[commit f2ee381ef3c2d1806cd3d4b311124fb590aa2a42](https://github.com/OpenTreeOfLife/reference-taxonomy/commit/f2ee381ef3c2d1806cd3d4b311124fb590aa2a42).

Where taxonomies conflict regarding taxon relationships, they are
resolved in favor of the higher priority taxonomy.  The priority
ordering is as given below.

## Sources

*   Taxonomy from: 
    DS Hibbett, M Binder, JF Bischoff, M Blackwell, et al. 
    A higher-level phylogenetic classification of the <i>Fungi</i>.
    [Mycological Research</i> <b>111</b>(5):509-547, 2007](http://dx.doi.org/10.1016/j.mycres.2007.03.004).
    Download location: Newick string with updates through June 2014
    archived at [http://dx.doi.org/10.6084/m9.figshare.915439](http://dx.doi.org/10.6084/m9.figshare.915439) .

*   Taxonomy from: SILVA 16S ribosomal RNA database, version 115.
    Download location: [http://www.arb-silva.de/download/arb-files/](http://www.arb-silva.de/download/arb-files/).
    See: Quast C, Pruesse E, Yilmaz P, Gerken J, Schweer T, Yarza P, Peplies J,
    Gl&ouml;ckner FO (2013) The SILVA ribosomal RNA gene database project:
    improved data processing and web-based tools. 
    [Nucleic Acids Research</i> 41 (D1): D590-D596](http://dx.doi.org/10.1093/nar/gks1219).

*   Index Fungorum.
    Download location: derived from database query result files provided by Paul
    Kirk, April 2014 (personal communication).
    Web site: [http://www.indexfungorum.org/](http://www.indexfungorum.org/).

*   Taxonomy from:
    Sch&auml;ferhoff, B., Fleischmann, A., Fischer, E., Albach, D. C., Borsch,
    T., Heubl, G., and M&uuml;ller, K. F. (2010). Towards resolving Lamiales
    relationships: insights from rapidly evolving chloroplast
    sequences. 
    [<i>BMC evolutionary biology</i> 10(1), 352.](http://dx.doi.org/10.1186/1471-2148-10-352).
    Download location: manually transcribed from the paper; see
    [here](https://github.com/OpenTreeOfLife/reference-taxonomy/tree/ott2.8/tax/713).

*   NCBI Taxonomy, from the 
    [US National Center on Biotechnology Information](http://www.ncbi.nlm.nih.gov/).
    Download location:
    [ftp://ftp.ncbi.nlm.nih.gov/pub/taxonomy/taxdump.tar.gz](ftp://ftp.ncbi.nlm.nih.gov/pub/taxonomy/taxdump.tar.gz)
    Updated frequently; for OTT 2.8 we used a version dated
    circa 11 June 2014.
    Web site: [http://www.ncbi.nlm.nih.gov/Taxonomy/](http://www.ncbi.nlm.nih.gov/Taxonomy/).
  </li>

*   GBIF Backbone Taxonomy, from the 
    [Global Biodiversity Information facility](http://www.gbif.org/).
    Download location: 
    [http://www.gbif.org/dataset/d7dddbf4-2cf0-4f39-9b2a-bb099caae36c](http://www.gbif.org/dataset/d7dddbf4-2cf0-4f39-9b2a-bb099caae36c).
    Updated from time to time.  We used a version dated 2013-07-02.

*   [Interim Register of Marine and Nonmarine Genera (IRMNG)](http://www.obis.org.au/irmng/), from CSIRO.
    Download location:
    [http://www.cmar.csiro.au/datacentre/downloads/IRMNG_DWC.zip](http://www.cmar.csiro.au/datacentre/downloads/IRMNG_DWC.zip).
    Updated from time to time.  We use a version dated 2014-01-31.
 

Any errors
should be assumed to have been introduced by the Open Tree of Life 
project until confirmed as originating in the source taxonomy.