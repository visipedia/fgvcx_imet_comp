![Banner](chenyang/assets/banner.png?raw=true)

# FGVCxiMet 2019 Challenge @ [FGVC6](https://sites.google.com/view/fgvc6/home), [CVPR 2019](http://cvpr2019.thecvf.com/)
The Metropolitan Museum of Art in New York, also known as the Met, has a diverse collection of over 1.5M objects of which over 300K have been digitized with imagery. The online cataloguing information is generated by Subject Matter Experts (SME) and includes a wide range of data. These include, but are not limited to: multiple object classifications, artist, title, period, date, medium, culture, size, provenance, geographic location, and other related museum objects within the Met’s collection. While the SME-generated annotations describe the object from an art history perspective, they can also be indirect in describing finer-grained attributes from the museum-goer’s understanding. Adding fine-grained attributes to the aid in the visual understanding of the museum objects will enable the ability to search for visually related objects.   

## iMet: The Met’s digitized collection for FGVCx
We present The Met’s digitized and annotated collection as a multi-attribute FGVCx challenge for CVPR 2018.  
### Images
As shown in the previous example, multiple modalities can be expected and are camera sources are unknown. Each artifact in the dataset has one or more in-focus photographs. The photographs are often centered for objects, and in the case where the museum artifact is an entire room, the images are scenic in nature.
### Annotations
The collection’s annotations are divided into two types: SME-derived attributes and crowd-labelled attributes.
#### SME-derived attributes
These attributes are provided at curation time. They are added by the SME as they see fit and may be a single label, or multiple labels with the possibility that some are added as free-form text.  We consider these annotations high quality.
#### Crowd-labelled attributes
Each object is seen by a single worker without a verification step.  Workers are advised to add multiple labels from an ontology provided by The Met, and additionally are allowed to add free-form text when they see fit.  The crowd are able to view the museum’s online collection pages and are advised to avoid annotating labels already present. Specifically, the crowd is advised to annotate labels related to what they “see” or what they infer as the object’s “utility.” We consider these annotations noisy.

Note that, we focus on utilizing the crowd-labelled attributes for the iMet challenge.
### Data sets
Although multiple attributes might exist for each data sample, we only keep one for simplicity.
#### Training set
TBD
#### Validation set
TBD
#### Testing set
TBD

This is an FGVCx competition as part of the [FGVC^6 workshop](https://sites.google.com/view/fgvc6/home) at [CVPR 2019](http://cvpr2019.thecvf.com/). 

## Competition Platform
We are using Kaggle to host the leaderboard.

## Dates
|||
|------|---------------|
Competition Starts |March, 2019|
Submission Deadline|Place holder, 2019|

