# Image Button for Qlik Sense

The **Image Button for Qlik Sense ** is a Qlik Sense extension to add image buttons to Qlik Sense.

## Sample 

![Alt text](./sample.png)

## Usage
To use this extension:

1. Unzip the downloaded zip file into "C:\Users\%USERNAME%\Documents\Qlik\Sense\Extensions\" folder.

2. Place the image files to "C:\Users\%USERNAME%\Documents\Qlik\Sense\Content\Default\" folder.

3. Add an load script statement to create a table with a column which includes image file names. In the following example, the column named "ImageFileName" includes file names stored on "C:\Users\%USERNAME%\Documents\Qlik\Sense\Content\Default\" folder.

    Load * Inline [
    ID,Category,ImageFileName
    1,Video recorder,VideoRecorder.png
    2,Air conditioner,AirConditioner.png
    3,Mobile phone,Mobile.png
    4,PC,PC.png
    5,TV,TV.png
    6,Video camera,VideoCamera.png
    ];

4. Place this extension on a Qlik Sense sheet, and add a dimension which stores image file names (the column named "ImageFileName" in the above example) to the extension. Sample Qlik Sense application using this extension is included in the project:

[Image Button Sample.qvf](https://github.com/mhamano/Qlik-Sense-Image-Button/blob/master/Image%20Button%20Sample.qvf) 

## Licence
The software is provided "AS IS" without warranty of any kind. This project is licensed under the terms of the MIT license.

## Author
Masaki Hamano