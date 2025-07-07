---
title: Adult mouse penis
---

# Adult Mouse Penis (3D)

Provided by the Pask Lab, University of Melbourne

2017 (GUDMAP)

## Introduction

{% capture content %}
{%
    include figure.html
    image="images/GUDMAP/adult_mouse_penis_atlas/3d-atlas-pn.png"
    caption="3D image of adult mouse genitourinary organ"
%}
{% endcapture %}

{% 
    include float.html
    content=content
    flip=true
%}

Mice are routinely used to study the development of the external genitalia and, in particular, the process of male urethral closure. This is because misplacement of the male penile urethra, or hypospadias, is amongst the most common birth defects reported in humans.

While mice present a tractable model to study penile development, several structures differ between mice and humans, and there is a lack of consensus in the literature on their annotation and developmental origins. Defining the ontology of the mouse prepuce is especially important for the relevance and interpretation of mouse models of hypospadias to human conditions.

We have developed a detailed annotation of the adult mouse penis that addresses these differences and **enables an accurate comparison of murine and human hypospadias phenotypes**. Through MRI data, gross morphology and section histology, we define the origin of the mouse external and internal prepuces, their relationship to the single human foreskin as well as provide a comprehensive view of the various structures of the mouse penis and their associated muscle attachments within the body. These data are combined to annotate structures in a novel 3D adult penis atlas that can be downloaded, viewed at any angle, and manipulated to examine the relationship of various structures.

{% include float.html clear=true %}

Refer to the [following publication](https://www.karger.com/Article/Pdf/431010) for a full explanation of the methodology:

> Phillips TR, Wright DK, Gradie PE, Johnston LA, Pask AJ. [A Comprehensive Atlas of the Adult Mouse Penis.](https://www.karger.com/Article/Pdf/431010) Sex Dev. 2015;9(3):162-72. doi: 10.1159/000431010. Epub 2015 Jun 19.

## MRI Viewing Instructions

1. Download and unzip the ZIP file (33 MB).
2. Download and install ITK-SNAP: [http://www.itksnap.org/pmwiki/pmwiki.php](http://www.itksnap.org/pmwiki/pmwiki.php)
3. Open the program and in the top toolbar go to `File` > `Open Main Image`, browse the above zip folder to locate the MRI Image labeled “Atlas.nii” in the "ITK-SNAP Files" folder. Then click `Next` >, then click `Finish`.
4. In the top toolbar go to `Segmentation` > `Open Segmentation`.
5. Open the file in the "ITK-SNAP Files" folder named "Segmentation.nii". Then click `Next >`, then click `Finish`.
6. In the top toolbar go to `Segmentation` > `Import Label Descriptions`.
7. Open the file in the "ITK-SNAP Files" folder named "label.txt". Then click `OK`.
8. In the bottom left hand window, click the `Update` button to bring up the 3D Penis image.

## Viewing Tips

- The 3D image can be rotated with the left click of the mouse.
- Right click and hold over the 3D image to zoom in and out.
- To turn off certain structures, find the `Segmentation Labels` section on the left sidebar. Click the dropdown menu under `Paint over`, click on the label you want to turn off, and in the editing window change its opacity to zero. This label is now invisible. To turn it back on, you can raise the opacity.
