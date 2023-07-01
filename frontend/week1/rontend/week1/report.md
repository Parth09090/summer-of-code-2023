
Parth Chavan
2022MS11891

As i am outside campus and don't have vpn i cannot access the moodle hence i am putting observations for google web page

HTML uses a hierarchical structure where elements are nested within each other, forming a tree-like representation.
![image](https://github.com/Parth09090/summer-of-code-2023/assets/137100541/3d85ca52-d564-4889-a4b8-661fbc6c6e68)
The basic structure of html looks like a tree and have elements nested inside each others
ex 
<html>
      <head></head>
        <body>
          
        </body>
</html>
As we can see in the image  ![image](https://github.com/Parth09090/summer-of-code-2023/assets/137100541/fe250321-670d-474b-a1cc-dd4082c54312)

inside the html tag there is a body tag inside which there is a div element inside which there are various div ,script etc elements
Indeed it forms a tree like a structure there is a main tag in which all of it's written like the tree's trunk then there are other tags like the branches which have tags inside them like small branches to the final leaves.

After selecting a element
I was able to edit some properties and also create some new properties to that element in the devtool
![image](https://github.com/Parth09090/summer-of-code-2023/assets/137100541/2b503a29-9609-4924-8892-854741701968)
As shown in the image after unchecking the align-items to center check box the Google shifted to left 
i was also able to change properties like font size font-style and it affected the grey color box in which about etc things are written
I also manged to change the background color behind the ggogle log to light blue
![image](https://github.com/Parth09090/summer-of-code-2023/assets/137100541/420e0956-8b23-45ba-b4b8-a499a7eb7805)
I was also able to add a border to the login box and increase it's padding which is the breathing space around the element

![image](https://github.com/Parth09090/summer-of-code-2023/assets/137100541/3d88e6ec-9ecd-4c2d-829b-365537b5cde9)
changed backgroud color to black 
Yeah so we can change totally how the page looks by using the devtools to by changing and editing the properties 

![image](https://github.com/Parth09090/summer-of-code-2023/assets/137100541/3f820d0d-c6bd-419c-a040-ef91b6fca4dd)
By default, web browsers cache static resources like CSS files, JavaScript files, and images to improve page loading speed. When the cache is enabled, subsequent page loads can retrieve these resources from the cache instead of downloading them again.
If we clear the memory and disk cache it will download the logos , images,scripts and links and hence the page loading time will be increased
![image](https://github.com/Parth09090/summer-of-code-2023/assets/137100541/008957e0-9ebc-41c3-ae98-305a43cab72f)
before removing cache finish time was something around 5sec now it became 8 sec
Disabling the cache in the Network tab means that the browser will always fetch the resources from the server, even if they haven't changed. This can increase the number of network requests and potentially slow down the page loading time, especially if there are many static resources to download.

 Network throttling is a feature in web browsers that allows us to simulate different network conditions, such as slow connections, to test how your website performs in those scenarios. When network throttling is enabled, the browser imposes artificial limitations on the network connection, which can significantly impact the loading time of resources. Large files may take longer to download, and the overall page loading speed may be noticeably slower.
 ![image](https://github.com/Parth09090/summer-of-code-2023/assets/137100541/3aaa20ee-5be0-4694-b462-e8464a52c6b5)
 

"CSS" stands for "Cascading Style Sheets." The term "cascading" in the context of CSS refers to the cascading behavior of styles from parent elements to child elements. The styles are applied in a cascading manner, starting from the top-level parent elements and propagating down the document tree.
 Some CSS properties are inherently inherited by default, meaning that if a parent element has a style defined for that property, its child elements will inherit that style unless explicitly overridden. Examples of inherited properties include color, font-family, font-size, line-height, text-align, etc.On the other hand, certain CSS properties are not inherited by default. These properties have no effect on their child elements unless explicitly specified. Examples of non-inherited properties include border, margin, padding, width, height, background-color, etc. These properties must be explicitly defined on each element if desired.

Buttons often have click event listeners attached to them. When we click on a button, the associated event listener function is executed, allowing the website to respond to the click event and perform the desired action. If we remove the event listener from a button, clicking the button would no longer trigger any specific action or behavior associated with that button. The button would essentially become non-interactive.

 The memory cache, also known as the RAM cache or memory store, is a component of a web browser that temporarily stores recently accessed web resources in the computer's memory. When a web page is loaded, the browser checks the memory cache first to see if it has a cached copy of the requested resources, such as HTML files, CSS stylesheets, JavaScript files, and images. If the resources are found in the memory cache, the browser retrieves them from memory, which is faster than downloading them from the network. This helps improve the overall performance and load times of web pages.
 The disk cache, also known as the hard disk cache or disk store, is a component of a web browser that stores web resources on the computer's hard drive. When resources are accessed, the browser may save copies of those resources in the disk cache. The disk cache allows the browser to serve cached resources from the local storage, rather than fetching them from the network again. 

Some resources on a web page might be generated dynamically based on user input or server-side processing. These dynamic resources may not be cached by default, and their content may not be included in the size of the page transferred. The size of dynamically generated content can vary based on user interactions or server responses, and it may not be accounted for in the initial transfer size also s memory cache and disk cache, play a role in reducing the amount of data that needs to be transferred. If a resource is already cached in the browser's cache, the browser may retrieve it from there instead of making a new request to the server. This can significantly reduce the amount of data transferred during subsequent page loads, resulting in a smaller size of the page transferred.
 
 



