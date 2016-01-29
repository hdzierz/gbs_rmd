# Convert to Fastq


```bash

run_pipeline.pl -configFile TagCountToFastq.xml
pandoc run.md -o run.html

```

```
## /software/x86_64/tassel-3.0/lib/gdpc.jar:/software/x86_64/tassel-3.0/lib/batik-util.jar:/software/x86_64/tassel-3.0/lib/wsdl4j-1.6.2.jar:/software/x86_64/tassel-3.0/lib/XmlSchema-1.3.1.jar:/software/x86_64/tassel-3.0/lib/xml.jar:/software/x86_64/tassel-3.0/lib/jfreechart-1.0.3.jar:/software/x86_64/tassel-3.0/lib/poi-3.0.1-FINAL-20070705.jar:/software/x86_64/tassel-3.0/lib/mail-1.4.jar:/software/x86_64/tassel-3.0/lib/commons-lang-2.1.jar:/software/x86_64/tassel-3.0/lib/commons-dbcp-1.2.1.jar:/software/x86_64/tassel-3.0/lib/xmlParserAPIs.jar:/software/x86_64/tassel-3.0/lib/biojava3-core-3.0.jar:/software/x86_64/tassel-3.0/lib/commons-discovery.jar:/software/x86_64/tassel-3.0/lib/ejml-0.13.jar:/software/x86_64/tassel-3.0/lib/axis2-kernel-1.2.jar:/software/x86_64/tassel-3.0/lib/jgrapht-0.5.3.jar:/software/x86_64/tassel-3.0/lib/geronimo-spec-activation-1.0.2-rc4.jar:/software/x86_64/tassel-3.0/lib/colt.jar:/software/x86_64/tassel-3.0/lib/axiom-api-1.2.4.jar:/software/x86_64/tassel-3.0/lib/batik-svg-dom.jar:/software/x86_64/tassel-3.0/lib/log4j-1.2.13.jar:/software/x86_64/tassel-3.0/lib/batik-ext.jar:/software/x86_64/tassel-3.0/lib/ssj.jar:/software/x86_64/tassel-3.0/lib/commons-codec-1.3.jar:/software/x86_64/tassel-3.0/lib/mysql-connector-java-3.1.13-bin.jar:/software/x86_64/tassel-3.0/lib/batik-awt-util.jar:/software/x86_64/tassel-3.0/lib/forester.jar:/software/x86_64/tassel-3.0/lib/batik-parser.jar:/software/x86_64/tassel-3.0/lib/commons-httpclient-3.0.1.jar:/software/x86_64/tassel-3.0/lib/commons-pool-1.3.jar:/software/x86_64/tassel-3.0/lib/axiom-impl-1.2.4.jar:/software/x86_64/tassel-3.0/lib/batik-dom.jar:/software/x86_64/tassel-3.0/lib/biojava3-phylo-3.0.jar:/software/x86_64/tassel-3.0/lib/crimson-parser.jar:/software/x86_64/tassel-3.0/lib/batik-gvt.jar:/software/x86_64/tassel-3.0/lib/batik-gui-util.jar:/software/x86_64/tassel-3.0/lib/commons-math-2.2.jar:/software/x86_64/tassel-3.0/lib/commons-logging-1.1.jar:/software/x86_64/tassel-3.0/lib/cisd-jhdf5-batteries_included_lin_win_mac.jar:/software/x86_64/tassel-3.0/lib/batik-xml.jar:/software/x86_64/tassel-3.0/lib/LiuExt.jar:/software/x86_64/tassel-3.0/lib/jung-1.7.5.jar:/software/x86_64/tassel-3.0/lib/commons-configuration-1.2.jar:/software/x86_64/tassel-3.0/lib/xercesImpl.jar:/software/x86_64/tassel-3.0/lib/lzma-4.63-jio-0.93.jar:/software/x86_64/tassel-3.0/lib/batik-svggen.jar:/software/x86_64/tassel-3.0/lib/batik-css.jar:/software/x86_64/tassel-3.0/lib/commons-collections-3.1.jar:/software/x86_64/tassel-3.0/lib/jcommon-1.0.6.jar:/software/x86_64/tassel-3.0/lib/junit-4.1.jar:/software/x86_64/tassel-3.0/lib/biojava3-alignment-3.0.jar:/software/x86_64/tassel-3.0/sTASSEL.jar
## Memory Settings: -Xms512m -Xmx1536m
## Tassel Pipeline Arguments: -configFile TagCountToFastq.xml
## [main] INFO net.maizegenetics.pipeline.TasselPipeline - Tassel Version: 3.0.158  Date: July 18, 2013
## net.maizegenetics.gbs.pipeline.TagCountToFastqPlugin
## [Thread-0] INFO net.maizegenetics.gbs.pipeline.TagCountToFastqPlugin - Opened the input file: ../02_MergedTagCounts/GBS_Workshop_Maize.cnt  nTags=41508
## tagsRead=1 tagsWritten=1 
## [Thread-0] INFO net.maizegenetics.gbs.pipeline.TagCountToFastqPlugin - CAGCAAAAAAAACACGTACTCCCTCCGTTTCTTTTTATTAGTCGCTGGATAGTGCAATTTTGCA
## [Thread-0] INFO net.maizegenetics.gbs.pipeline.TagCountToFastqPlugin - Finished reading input file.
## Finished converting binary tag count file to fastq.
## Total number of tags read: 41508
## Total number of tags written: 41509 (above minCount of 5)
## Ouput fastq file: ./GBS_Workshop_Maize.fq
## 
## 
## pandoc: run.md: openFile: does not exist (No such file or directory)
```