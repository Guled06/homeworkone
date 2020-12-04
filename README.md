# marketing-agency

I spaced out the source code, so it would be easy to read when the need arises to change something within the source code.

I changed the header from a -div- to just a header, by removing the -div-. 

I also changed the first -div- underneath the -span- to just a -nav-. The -div- element was non-semantic, and when I changed it to the -nav- element, the code became more semantic. The images containing within this -nav- were grouped together properly.

<img src="https://www.w3schools.com/html/img_sem_elements.gif" alt="different elements">

On number 39 on the index.html, I changed the -div- which contained a class that equaled to a content. I changed it to just a -main- element without a class. This helps the developer understand that all the things within this content is the main component.

WIthin the main content/component I changed into sections. There are sub-sections within the main content. It would make sense to have -section- underneath the -main-.

<img src="https://miro.medium.com/max/5628/1*VtY_Fs3cAigxw9blic8Ayg.jpeg" alt="how to use it">


Afterwards, I created am aside content that contains articles within the aside content. The aside content is similar to the main content. It can stand on it's own, but at the same time it is not the main content. The aside conent has it's own text and images, just like the main conent. But, since the main content has -section- contents within, I created something called -article- contents within the aside content. This way, I know that within the main -main- content there are -section- sub-sections, and the secondary aside -aside- content, there is an -article- sub-sections. This helps reorganize what is what within the body of the html. 

<img src="https://www.bluetext.com/wp-content/uploads/2016/07/marketing-image-1-2.jpg" alt="organize">

I refactored the selectors that shared the same property and value into a single selector instead of re-writing the same selectors with the same property and values. By doing this, my style.css was easily readable and organized. 

<img src="https://i.ytimg.com/vi/KfZlymzh2CA/hqdefault.jpg" alt="refactored">
