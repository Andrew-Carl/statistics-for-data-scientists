# statistics-for-data-scientists
Code associated with the book "<a target="_blank" href="https://www.amazon.com/gp/product/1491952962/ref=as_li_tl?ie=UTF8&camp=1789&creative=9325&creativeASIN=1491952962&linkCode=as2&tag=andrewtcarl-20&linkId=fe081eb551d518ca409ce4694173e491">Practical Statistics for Data Scientists: 50 Essential Concepts</a><img src="//ir-na.amazon-adsystem.com/e/ir?t=andrewtcarl-20&l=am2&o=1&a=1491952962" width="1" height="1" border="0" alt="" style="border:none !important; margin:0px !important;" />"

The scripts are stored by chapter and replicate most of the figures and code snippets.

HOW TO GET THE DATA:
Run R script:
The data is not saved on github and you will need to download the data.
You can do this in R using the sript src/download_data.r. This will copy the data into the data directory ~/statistics-for-data-scientists/data. 

Manual download:
Alternatively, you can manually download the files from  https://drive.google.com/drive/folders/0B98qpkK5EJemYnJ1ajA1ZVJwMzg
or from  https://www.dropbox.com/sh/clb5aiswr7ar0ci/AABBNwTcTNey2ipoSw_kH5gra?dl=0

IMPORTANT NOTE: 
The scripts all assume that you have cloned the repository into the top level home directory (~/)
If you save the repository elsewhere, you will need to edit the line

  PSDS_PATH <- file.path('~', 'statistics-for-data-scientists')

to point to the appropriate directory in all of the scripts.

  PSDS_PATH <- <<pathname I am using>>
>>>>>>> 321b878750602e233aad8a0a7814a8f5ceb99cf0
