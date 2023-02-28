Another community contract for Hactoria !


We have an instagram account : 
https://www.instagram.com/ameliac008/

Which leads to a telegram bot where we can obtain a zip file.
The zip file is passwordless and contains 6 images.
The JPG files does not contains any steg or hidden informations.

In each PNG image we have a code on the left corner : 
![[Pasted image 20230227212158.png]]

If we look on google, it seems to be coordinates.
We can convert them on What3words

- First page : 24.116824, 49.060283 > ///conveying.milling.camped
- second page : 25.069815, 48.197507 > ///keyholes.redundant.imagine
- third page : 22.688910, 54.102856 > ///half.camping.auction

The 3 words are `conveying-keyholes-half` but we need only two.
We "bruteforce" the passphrase with these combinations : 
conveying-keyholes
conveying-half >>> THIS ONE'S GOOD !

![[Pasted image 20230228164635.png]]
