    usage: dcm2pdf [<options>] <dicom-file> <pdf|cda|stl|mtl|obj|genozip-file>
    or dcm2pdf [Options] <dicom-file>... <pdf|cda|stl|mtl|obj|genozip-outdir>
    or dcm2pdf [Options] <dicom-dir>... <pdf|cda|stl|mtl|obj|genozip-outdir>
    
    Convert DICOM file(s) to PDF (file extension pdf), CDA (file extension
    xml), STL (file extension stl), MTL (file extension mtl), OBJ (file
    extension obj) or Genozip compressed genomic (file extension genozip)
    files(s).
    -
    Options:
     -h,--help      display this help and exit
     -V,--version   output version information and exit
    -
    Example 1: dcm2pdf object.dcm file.pdf
    => Convert Encapsulated PDF DICOM object to a pdf file.
    -
    Example 2: dcm2pdf cda-object.dcm cda-file.xml
    => Convert Encapsulated CDA DICOM object to a CDA file.
    -
    Example 3: dcm2pdf object1.dcm object2.dcm pdf-dir
    => Convert the specified Encapsulated PDF DICOM objects to pdf files in
    pdf-dir.
    -
    Example 4: dcm2pdf dicom-object-dir pdf-dir
    => Convert the Encapsulated PDF DICOM objects in dicom-object-dir to pdf
    files in pdf-dir.