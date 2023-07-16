# Frontend Frameworks
## Table of contents:
* Scenario & solution
* Documentations map
* Documentation
* Contribution
* License
## Scenario
You are a beginner javascript developer in the frontend/fullstack world. One daty you wanted to see these "frameworks" (Eg- Svelte, React, Vue, etc.) that many people use. But frameworks take a long time to use and test out.
## Solution
This repository helps to see which framework is good for your needs and then document them below. Keep in mind that the things take time to document so patience would be appreciated :). This might not document everything but you can tell me new ideas. (see contribution)
## Documentation map
**Note**: Anything here is not an framework of any sort. After the line, anything shown **is completly fake**. Also "FN" means Framework name.

---

### Framework name 

**TTYL**:  Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. 


Example-
```javascript
const example = 0;
console.log(example)

function logger() {
  console.log("hello world!")
}
```


Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

#### FN pros
Lorem ipsum dolor sit amet, consectetur adipiscing elit.
1. List
2. List
3. List
4. List
5. List
6. (There can be more or less)

#### FN cons
Lorem ipsum dolor sit amet, consectetur adipiscing elit.
1. List
2. List
3. List
4. List
5. List
6. (There can be more or less)
#### Why will I use FN?
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

---
<h2>Documentation</h2>

<p><b>Note</b>:  Here comes the part! Remember that this is still in progress, and will be made later. Documentation starts after this line.</p>


---


### Svelte
**TTYL**: Svelte is one of the most popular frameworks. This is the framework I use the most. It is an incredibly fast framework that consist of useful features while easy to use. It has its own file extension called `.svelte` as well as a npm registry ran by `npm install svelte`. Run that command to get started. Here is a basic counter on svelte

`app.svelte`
```svelte
<script>
  let count = 0
  function handleclick() {
  count++;

  }
</script>

<button on:click= {handleclick()}>counted {count} {(count == 1) ? "time" : "times"}</button>
``` 
Simple code is all you need some time. Look in the "Svelte" directory for more. But sometimes it does not have IDE support and has a really small open source community.

Svelte pros:
1. Svelte effectevly and accurately compiles code to javascript.
2. The browser dosen't convert the DOM, that means no virtual DOM.
3. Includes its own management system.
4. The compliling is so good, it does not leave a single trace of svelte (unless you gave a comment like `// svelte!` or something).

Svelte cons:
1. Its a relatively new framework and has a small community.
2. Not many devtools to rely on.
3. Small open source ecosystem

#### Why do I use svelte?
Svelte is used for small programs. Its opensource so you can rely on their code. But since its not a big framework with more functions like react, you can't trust it on big apps. A very fast application too!

