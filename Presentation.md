---
marp: true
html: all
theme: gaia
---
# Title slide
This page is the title slide

<style>
#current-time {
    color: blue;
}
</style>

<iframe width="100%" height="400px" style="border: none;" src="https://godbolt.org/e#g:!((g:!((g:!((h:codeEditor,i:(filename:'1',fontScale:14,fontUsePx:'0',j:1,lang:c%2B%2B,selection:(endColumn:2,endLineNumber:8,positionColumn:2,positionLineNumber:8,selectionStartColumn:2,selectionStartLineNumber:8,startColumn:2,startLineNumber:8),source:'//+Type+your+code+here,+or+load+an+example.%0Aint+square(int+num)+%7B%0A++++return+num+*+num%3B%0A%7D%0A%0Aint+main()+%7B%0A++++square(5)%3B%0A%7D'),l:'5',n:'0',o:'C%2B%2B+source+%231',t:'0')),k:51.17073355849874,l:'4',n:'0',o:'',s:0,t:'0'),(g:!((h:compiler,i:(compiler:g152,filters:(b:'0',binary:'1',binaryObject:'1',commentOnly:'0',debugCalls:'1',demangle:'0',directives:'0',execute:'0',intel:'0',libraryCode:'0',trim:'1',verboseDemangling:'0'),flagsViewOpen:'1',fontScale:14,fontUsePx:'0',j:1,lang:c%2B%2B,libs:!(),options:'',overrides:!(),selection:(endColumn:1,endLineNumber:1,positionColumn:1,positionLineNumber:1,selectionStartColumn:1,selectionStartLineNumber:1,startColumn:1,startLineNumber:1),source:1),l:'5',n:'0',o:'+x86-64+gcc+15.2+(Editor+%231)',t:'0')),k:48.82926644150127,l:'4',m:100,n:'0',o:'',s:0,t:'0')),l:'2',n:'0',o:'',t:'0')),version:4"></iframe>

<div id="current-time"></div>

<script>
  // Your client-side JavaScript code here
  console.log("Hello from Marp!");
  // Example: Display current time
  document.addEventListener('DOMContentLoaded', (event) => {
    const timeElement = document.getElementById('current-time');
    if (timeElement) {
      timeElement.textContent = new Date().toLocaleTimeString();
    }
  });
</script>

---

# Slide Overview
- Topic 1
- Topic 2
- Topic 3
