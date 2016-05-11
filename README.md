# BarcodeReader

**NOTES: 
<p>
Apple provides default framework to detect barcodes with <b>AVFoundation</b> framework. 
The supported types are: <br/>
      UPC-A,  UPC-E,  Code 39,  Code 39,  mod 43,  Code 93,  Code 128,  EAN-8,  EAN-13,  Aztec,  PDF417,  QR
<p/>
<p>
I have used this framework and was able to read all kind of barcodes,qr codes available online. like -

<img src="https://upload.wikimedia.org/wikipedia/commons/0/07/Better_Sample_PDF417.png"><br/>

<img src="http://availableupc.com/sites/default/files/defaultupc.jpg"><br/>

<img src="https://upload.wikimedia.org/wikipedia/commons/2/2d/Qr-3.png"><br/>

<p/>
<p>
After some research i have found out that most NIDs or Licenses use "PDF417" type of 2D barcodes.The app was able to read sample PDF417 barcodes,But it was not able to read our Local "National ID" cards barcode.
<p/>
<p>
However after trying to read NID barcodes with different camera settings and optimization unsuccessfully, i found one third party SDK that supports PDF417 type barcodes,with that SDK, was able to read our Local "National ID" cards barcode.
<p/>
<p>
So, i have included both implementation in the project.
<p/>

