# iMerge tag count files


```bash

run_pipeline.pl -configFile MergeTagCounts.xml

```

```
## /software/x86_64/tassel-3.0/lib/gdpc.jar:/software/x86_64/tassel-3.0/lib/batik-util.jar:/software/x86_64/tassel-3.0/lib/wsdl4j-1.6.2.jar:/software/x86_64/tassel-3.0/lib/XmlSchema-1.3.1.jar:/software/x86_64/tassel-3.0/lib/xml.jar:/software/x86_64/tassel-3.0/lib/jfreechart-1.0.3.jar:/software/x86_64/tassel-3.0/lib/poi-3.0.1-FINAL-20070705.jar:/software/x86_64/tassel-3.0/lib/mail-1.4.jar:/software/x86_64/tassel-3.0/lib/commons-lang-2.1.jar:/software/x86_64/tassel-3.0/lib/commons-dbcp-1.2.1.jar:/software/x86_64/tassel-3.0/lib/xmlParserAPIs.jar:/software/x86_64/tassel-3.0/lib/biojava3-core-3.0.jar:/software/x86_64/tassel-3.0/lib/commons-discovery.jar:/software/x86_64/tassel-3.0/lib/ejml-0.13.jar:/software/x86_64/tassel-3.0/lib/axis2-kernel-1.2.jar:/software/x86_64/tassel-3.0/lib/jgrapht-0.5.3.jar:/software/x86_64/tassel-3.0/lib/geronimo-spec-activation-1.0.2-rc4.jar:/software/x86_64/tassel-3.0/lib/colt.jar:/software/x86_64/tassel-3.0/lib/axiom-api-1.2.4.jar:/software/x86_64/tassel-3.0/lib/batik-svg-dom.jar:/software/x86_64/tassel-3.0/lib/log4j-1.2.13.jar:/software/x86_64/tassel-3.0/lib/batik-ext.jar:/software/x86_64/tassel-3.0/lib/ssj.jar:/software/x86_64/tassel-3.0/lib/commons-codec-1.3.jar:/software/x86_64/tassel-3.0/lib/mysql-connector-java-3.1.13-bin.jar:/software/x86_64/tassel-3.0/lib/batik-awt-util.jar:/software/x86_64/tassel-3.0/lib/forester.jar:/software/x86_64/tassel-3.0/lib/batik-parser.jar:/software/x86_64/tassel-3.0/lib/commons-httpclient-3.0.1.jar:/software/x86_64/tassel-3.0/lib/commons-pool-1.3.jar:/software/x86_64/tassel-3.0/lib/axiom-impl-1.2.4.jar:/software/x86_64/tassel-3.0/lib/batik-dom.jar:/software/x86_64/tassel-3.0/lib/biojava3-phylo-3.0.jar:/software/x86_64/tassel-3.0/lib/crimson-parser.jar:/software/x86_64/tassel-3.0/lib/batik-gvt.jar:/software/x86_64/tassel-3.0/lib/batik-gui-util.jar:/software/x86_64/tassel-3.0/lib/commons-math-2.2.jar:/software/x86_64/tassel-3.0/lib/commons-logging-1.1.jar:/software/x86_64/tassel-3.0/lib/cisd-jhdf5-batteries_included_lin_win_mac.jar:/software/x86_64/tassel-3.0/lib/batik-xml.jar:/software/x86_64/tassel-3.0/lib/LiuExt.jar:/software/x86_64/tassel-3.0/lib/jung-1.7.5.jar:/software/x86_64/tassel-3.0/lib/commons-configuration-1.2.jar:/software/x86_64/tassel-3.0/lib/xercesImpl.jar:/software/x86_64/tassel-3.0/lib/lzma-4.63-jio-0.93.jar:/software/x86_64/tassel-3.0/lib/batik-svggen.jar:/software/x86_64/tassel-3.0/lib/batik-css.jar:/software/x86_64/tassel-3.0/lib/commons-collections-3.1.jar:/software/x86_64/tassel-3.0/lib/jcommon-1.0.6.jar:/software/x86_64/tassel-3.0/lib/junit-4.1.jar:/software/x86_64/tassel-3.0/lib/biojava3-alignment-3.0.jar:/software/x86_64/tassel-3.0/sTASSEL.jar
## Memory Settings: -Xms512m -Xmx1536m
## Tassel Pipeline Arguments: -configFile MergeTagCounts.xml
## [main] INFO net.maizegenetics.pipeline.TasselPipeline - Tassel Version: 3.0.158  Date: July 18, 2013
## [main] INFO net.maizegenetics.gbs.pipeline.MergeMultipleTagCountPlugin - Merging the following .cnt files...
## [main] INFO net.maizegenetics.gbs.pipeline.MergeMultipleTagCountPlugin - /powerplant/workspace/cfphxd/gbs_moa/02_TagCounts/02_MergedTagCounts/../01_IndividualTagCounts/C08L7ACXX_6.cnt
## [main] INFO net.maizegenetics.gbs.pipeline.MergeMultipleTagCountPlugin - ...to "./GBS_Workshop_Maize.cnt".
## net.maizegenetics.gbs.pipeline.MergeMultipleTagCountPlugin
## [Thread-0] INFO net.maizegenetics.gbs.pipeline.MergeMultipleTagCountPlugin - Opened :/powerplant/workspace/cfphxd/gbs_moa/02_TagCounts/02_MergedTagCounts/../01_IndividualTagCounts/C08L7ACXX_6.cnt tags=159307
## B::0:[Thread-0] INFO net.maizegenetics.gbs.pipeline.MergeMultipleTagCountPlugin - 
## t=0 tagsRead=1 outCnt=0 rwOpen=1 
## A:0:0:[Thread-0] INFO net.maizegenetics.gbs.pipeline.MergeMultipleTagCountPlugin - 
## [Thread-0] INFO net.maizegenetics.gbs.pipeline.MergeMultipleTagCountPlugin - CAGCAAAAAAAAAAAAACAAAATATAAAGCTCCTGTAGTATAATAATGCCCACTAACTCGCGCA
## [Thread-0] INFO net.maizegenetics.gbs.pipeline.MergeMultipleTagCountPlugin - Finished reading file 0.
## [Thread-0] INFO net.maizegenetics.gbs.pipeline.MergeMultipleTagCountPlugin - Adding header to ./GBS_Workshop_Maize.cnt.
```