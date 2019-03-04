### How to make the `Hello World` web component on github pages

Let's create a simple web component that will display the words "Hello World".


```html
<hello-world></hello-world>

 <script>
     class HelloWorld extends HTMLElement {
       constructor(){
         super();
         this.innerText = "Hello World";
       }
     }
     customElements.define("hello-world", HelloWorld);
 </script>
 
```
1. Create the `index.html` file and place the code above in it.
2. Now we need to upload the file to `github`. To do this we need to:
   1. Login to account.
   2. In the upper right corner, click on the "+" tab and select "New repository" from the drop-down list.
   3. In the page that appears, in the field with the name "Repository Name" enter the name of the future repository. 
   Let's call it "WebComponent". You can also add a description that briefly explains the essence of the project.
   4. After that, click the `Create repository` button to finish creating an **`empty`** repository.
3. ala