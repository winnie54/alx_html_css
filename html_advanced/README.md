**HTML_ADVANCED**
_For this project,i will be implementing from scratch a designer webpage_
see also [figmapage](https://intranet.alxswe.com/rltoken/aGNsZzxZE92XAjRXDT0b4A)
1. Header
mandatory
Let’s start by the top: the header

Here the wireframe of it:
![header wireframe](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2021/4/415b0226fd338ff76a330b371fc83c9224254c47.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20230706%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20230706T102254Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=5d44c820b428d83c3f777b1533e3779ff2182e13b7071ff5b66c54e01a41c192)
* Create the HTML skeleton (html, head, body, etc.)
* In the body, add an header tag
* Inside this header:
* Add a link element with an image inside
* Add a block of 3 link elements
2. Banner
mandatory
Now, the banner under the header:
![Banner](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2021/4/ee07503a513036f49d73b31df339ee798f9f277f.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20230706%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20230706T102254Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=16a3b8d2b05218abe340f49f2d4d4a1cc260acde0042eb2999f1d8937dbb789d)
Under the header, add a main element with inside a section element.

In this section element, add:
* A block with inside:
* An heading tag (don’t forget to use the correct heading value)
* A text element
* A button tag
* Another block with inside:
    * Another heading tag (same, be careful about which one you are using)
    * A block containing 4 blocks - each block with inside:
    * An image
    * An heading tag
    * A text
3. Quote
mandatory
Under the banner, we will add the quote block:
![quote](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2021/4/25b4264f9266962bffb39791b265317cc5ff8147.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20230706%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20230706T102254Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=976403ea26fcbce76ee22a5589c9097e7d16d9aab06e742c14cb033e777111a8)
The quote section is inside the main:
* Create a new section for the quote
* Inside, add a block containing:
* An image
* Another block with inside:
    * A quote tag
    * An author quote
    * A text
4. Videos
mandatory
Let’s now add the videos list:
![videos](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2021/4/a5712ac70330c6812c6aee2bf21efe7ac53d1397.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20230706%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20230706T102254Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=8da37e23483a0b9f9c9ca6656ff87145abb3292e46a9a74403cb4a2283d67416)
New section with inside:

An heading tag
A block containing the 4 video block - each of them are composed with:
An image
An heading
A text
A block for the author:
    * A image
    * An heading
    * A block for the rating:
    * A block of images (one star = one image)
    * A text
5. Membership
mandatory
Membership section is similar as the videos list:
![membership](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2021/4/1ddf18bc6d89725de2fde4881e8990fae6d89628.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20230706%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20230706T102254Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=c1d0f3b0a934ed8f60284f242e2ad09b48f3cd6d89e04603c4c48373bb7421a4)
After the videos list section, add a new section containing:
    An heading
    A block with inside 4 block item - each block defined with:
    An image
    An heading
    A text
    A button
6. FAQ
mandatory
The FAQ section is ending the page before the footer:
![F.A.Q](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2021/4/e4b2806abe9edc126fa0d4155aaf5d7e7da479e4.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20230706%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20230706T102254Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=793933a0348d4c207880514edd6ae7422be8cbb909c7ae01f40c99cb828be2eb)
Add a section for the FAQ with inside:
    * A block that contains 2 “row block”
    *  Each “row block” contains 2 “item block”
    * Each “item block” is composed of:
    * An heading
    * A text
7. Footer
mandatory
And… the footer!
After the last section, outside of the main, add a footer:
8 A global block (used later for centering the footer content), inside this block:
    * A “row block” with:
    * An image
    * A block with inside:
    *Images with link
    * A text
And… that’s it for the moment - the result should not be shiny, don’t worry, CSS is coming…
![smile](https://miro.medium.com/v2/resize:fit:720/format:webp/1*GvpK9-2unOPPSuN7E5VlZg.jpeg)
