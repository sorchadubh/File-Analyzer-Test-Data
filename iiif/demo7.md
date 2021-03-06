# Generate Manifest with EAD Subject Ranges and Digital Object References

{% include nav.html %} 

In this example, we will also include digital objects (DAO's) defined within the EAD into the manifest.

![Index by EAD and DAO](tutorial-screenshots/IIIFScenarios/Slide8.JPG)

## Step 1: In manifestGenerate.prop, set ManifestMetadataInputFile to "[dogPhotosEADWithLinkedDAO.xml]({{site.src_path}}/iiif/dog-photos/dogPhotosEADWithLinkedDAO.xml#L135-L145)"

    # Manifest Metadata Input File
    ManifestMetadataInputFile: dogPhotosEADWithLinkedDAO.xml

## Step 2: On the "File Test Properties" tab of "Criteria" tab, keep the Project Value Translator to "EADFolderMapSubjectsOnly"

Then click "Analyze"...

![Screenshot](tutorial-screenshots/fad6.png)

## Step 3: Preview the results in Universal Viewer

Note the additional items that have been imported by Digital Object URL in the EAD.

![Screenshot](tutorial-screenshots/uv7.png)

![Screenshot](tutorial-screenshots/uv7a.png)

{% include nav.html %} 
