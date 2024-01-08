# Pdf-To-Image-Convertor
This repository provides tools to scrape PDF links from webpages, convert these PDFs into images, and manage the resulting image files.
This tool facilitates the conversion of PDF documents to images, offering both scraping capabilities for web-based PDFs and direct conversion functionalities.

# Workflow:
Scraping PDF Links [https://github.com/Shreya2803/Pdf-To-Image-Convertor/blob/main/PDF2Image.ipynb] :

The tool identifies and extracts PDF links from specified webpages.
Cons: Some links may not exist or might point to different language PDFs. It's advisable to manually check and filter the links before proceeding.
Converting PDFs to Images:

# Direct PDF Links: 
[https://github.com/Shreya2803/Pdf-To-Image-Convertor/blob/main/PDF2Image.ipynb]
<br>
The tool directly converts the PDFs from the provided links into images.
Cons: Not all PDF links might be directly convertible. If issues arise, the PDFs need to be downloaded first and then processed.
# From Downloaded PDFs:
If the direct conversion fails, users can manually download the PDFs and provide their paths for conversion.
Cons: For platforms like Google Colab without a pro version, it's recommended to process a limited number of PDFs at once due to potential resource constraints.
# File Count:

After conversion, the tool provides a count of images saved in each directory. This count offers an overview of the number of images generated from the provided PDFs.
Notes:
For efficient processing and to avoid potential issues, it's recommended to process a limited number of larger PDFs at a time.
Regularly check the image counts in directories to monitor the progress and ensure all desired images have been generated.
# Functionality :
There are many web pages that offer pdf to image conversion and zipped folder download . But for bulk number of pdf conversion this comes with a price to pay and mostly all those webpages come with pro version .This open source tools can be accessed to convert bulk sized and number of pdfs to convert into images.
# Upcoming : 
The following features will be introduced later
1) Converted files to be  downloaded in Zip Folder.
2) Efficiency of the code ( To have less trouble in assigning the variable)

# Contributing:
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
