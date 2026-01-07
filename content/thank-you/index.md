<?xml version='1.0' encoding='UTF-8'?>
<qgis projectname="Carrieres_RA" version="3.28.0">
  <layer-tree-group name="Carrières Rhône-Alpes">
    <layer-tree-layer name="Carrières AuRA (WFS filtré)" id="carrieres_wfs" source="url=https://datacarto.open-datara.fr/wfs/99448a13-e009-4bb2-bb2b-755aec6ecead|typename=l_carriere_s_r84|version=1.0.0" provider="WFS" />
  </layer-tree-group>
  <maplayer type="vector" name="Carrières AuRA (WFS filtré)" id="carrieres_wfs" geometry="Point" provider="WFS">
    <datasource>url=https://datacarto.open-datara.fr/wfs/99448a13-e009-4bb2-bb2b-755aec6ecead|typename=l_carriere_s_r84|version=1.0.0</datasource>
    <layername>Carrières AuRA (WFS filtré)</layername>
    <srs>
      <spatialrefsys>
        <proj4>+proj=longlat +datum=WGS84 +no_defs</proj4>
        <srid>4326</srid>
        <authid>EPSG:4326</authid>
      </spatialrefsys>
    </srs>
    <renderer-v2 type="singleSymbol" symbollevels="0">
      <symbols>
        <symbol name="0" type="marker" alpha="1" clip_to_extent="1">
          <layer class="SimpleMarker" locked="0">
            <prop k="color" v="64,181,246,255"/>
            <prop k="outline_color" v="26,35,126,255"/>
            <prop k="outline_width" v="0.5"/>
            <prop k="size" v="3"/>
            <prop k="name" v="circle"/>
          </layer>
        </symbol>
      </symbols>
    </renderer-v2>
    <layer-opacity>1</layer-opacity>
    <layer-geometry-type>Point</layer-geometry-type>
    <layer-filter>"code_insee" LIKE '01%' OR "code_insee" LIKE '38%' OR "code_insee" LIKE '69%' OR "code_insee" LIKE '73%' OR "code_insee" LIKE '74%'</layer-filter>
  </maplayer>
</qgis>
---
type: "page"
title: "Thank you for choosing QGIS!"
draft: false
HasBanner: false
sidebar: true
url: "/download/thank-you"
---

{{< content-start >}}

# Thank you for choosing QGIS!

## Your freshly baked copy of QGIS is downloading. 

{{< progress-bar autoHideAfter="60000">}}

{{< rich-box-start icon="⬇️" layoutClass="tips">}}
{{< rich-content-start themeClass="coloring-1" >}}
##### Monitor Your Download
Downloads may take a while. Please **monitor the progress** using your **download manager**.

If your download didn't start, you can manually download QGIS from the [QGIS.org hosted downloads](https://download.qgis.org/downloads/).
{{< rich-content-end >}}
{{< rich-box-end >}}


{{< rich-box-start mode="html" layoutClass="has-right" id="donate-prompt">}}
{{< rich-content-start themeClass="coloring-2" >}}
## Your support is vital to keep QGIS improving

Our software is, and always will be, available free of charge if downloaded from QGIS.org.

The project is a result of a huge effort and social contribution from many community members who volunteer their time and expertise. In addition, many businesses, government agencies and commercial entities have contributed to the development of QGIS. They do this either to ensure that QGIS meets their specific needs or to contribute to and accelerate the huge social impact that is realised by making a tool such as QGIS freely available. Our goal is the betterment of society through informed spatial decision making. If you are able, we gently request that you support our work.

Whether you choose to donate or not, we hope that you enjoy using our labour of love and encourage you to share and spread your downloaded copy far and wide so that others may enjoy it too.

Our very best regards!

{{< rich-content-end >}}
{{< rich-right-start mode="html" >}}
<!-- {{< stripe-widget otherMethods="true" alreadyDonated="true">}} -->
{{< payrexx-widget otherMethods="true" alreadyDonated="true">}}
{{< rich-right-end >}}
{{< rich-box-end >}}

{{< rich-box-start layoutClass="qgis_first_conference mt-6">}}
{{< rich-content-start >}}
![QGIS Developers 1st meeting](qgis_1st_conference.png "QGIS Developers 1st meeting")
{{< rich-content-end >}}
{{< rich-box-end >}}


{{< rich-box-start icon="🛟" layoutClass="tips mt-6 mb-6">}}
{{< rich-content-start themeClass="coloring-1" >}}
##### Tips for first launch
If you have any questions while starting QGIS, welcome to our complete guide to installing for the first time.
<a href="/resources/installation-guide">Installation guide  </a>
{{< rich-content-end >}}
{{< rich-box-end >}}

## What's next?

For testing and learning purposes, [a sample dataset is available](https://docs.qgis.org/latest/en/docs/user_manual/introduction/getting_started.html#downloading-sample-data), which contains collections of data from different sources and in different formats.

You can also look at the cases - there are many inspiring stories there.

{{< rich-box-start layoutClass="has-right" mode="html" >}}
{{< rich-content-start themeClass="coloring-1" >}}
### Case Studies

We gather inspiring stories from actual users that showcase the versatility and power of the QGIS solution

[Find out more]({{< ref "project/case-studies.md" >}})
{{< rich-content-end >}}
{{< rich-right-start >}}  
{{< usecase >}}
{{< rich-right-end >}}
{{< rich-box-end >}}

{{< rich-box-start layoutClass="has-right rounded" mode="html" >}}
{{< rich-content-start themeClass="coloring-2" >}}
### Local user groups

Join a community of like-minded individuals in your region.

[Local groups list]({{< ref "community/groups.md" >}})
{{< rich-content-end >}}
{{< rich-right-start >}}  
![Local user groups](../../project/img/groups.jpg "Local user groups")
{{< rich-right-end >}}
{{< rich-box-end >}}



{{< content-end >}}
