# MY-IMAGE-AVIGAIL

    This is a python application which gets images and creates a PDF file in a folder called “output” with all the images printed in it.

## Build

    docker build -t convertor .

## run

    docker run -it --name myContainer -e PDF_Avigail -v $PWD/images:/app/images -v $PWD/output:/app/output convertor images output