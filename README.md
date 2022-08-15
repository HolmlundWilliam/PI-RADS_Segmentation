# Prostate Segmentation according to the PI-RADS standard using a 3D-CNN

**Welcome**,
to the GitHub page of my Master Thesis Project.
This page will provide links to the Thesis report, the software *HERO* - for which the model will be implemented in the free version, as well as a link to download the trained model as a frozen graph (from TensorFlow), ready to use in Python.

The Thesis aimed to create an automatic solution for segmentation of the prostate and its internal anatomical zones from MR images, as this can be a very time-consuming task if performed manually.
The result is this 3D-CNN model.


--

Later this fall, the model will be available in the free version of *HERO* (www.heroimaging.com) - a graphical programming platform that enables complex image analysis, in an easy and interactive way.

This will be the easiest and most straight-forward way of using the model - although some patience is still needed.


The model takes a T2 MRI prostate (DICOM) image as input and returns a segmented multilabel (DICOM) image with the anatomical zones as output - which can also easily be separated into individual RTSTRUCTs.

To try the model on a larger dataset (n=98), one can use the PROSTATEx dataset from the Cancer Imaging Archive, avaliable at:

https://wiki.cancerimagingarchive.net/pages/viewpage.action?pageId=70230177

*One important note is that this is the dataset that has been used as a basis for the training of the model, and thus any results on this dataset will be "exaggerated" - although it still works as a way to try out the model.*

--

The trained model is also available as a frozen graph (from TensorFlow), which can be used directly in Python.

...
Something about the preprocessing and postprocessing!!
...

Model available at:

https://nonpi.s3.eu-north-1.amazonaws.com/mtk/resources/model-zoo/0005.pb

---

For the interested reader that would like to know more about the project, the full Thesis report is avaliable to download as a pdf at:

https://www.diva-portal.org/smash/record.jsf?dswid=-4000&pid=diva2%3A1654535&c=2&searchType=SIMPLE&language=sv&query=william+holmlund&af=%5B%5D&aq=%5B%5B%5D%5D&aq2=%5B%5B%5D%5D&aqe=%5B%5D&noOfRows=50&sortOrder=author_sort_asc&sortOrder2=title_sort_asc&onlyFullText=false&sf=all
