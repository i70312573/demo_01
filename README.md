# demo_01
<div id="header" align="center">
  <img src="https://media.giphy.com/media/M9gbBd9nbDrOTu1Mqx/giphy.gif" width="100"/>
</div>

## **demo_01
<div id="badges">
  <img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge"/>
  <img src="https://img.shields.io/badge/YouTube-red?style=for-the-badge&logo=youtube&logoColor=white" alt="Youtube Badge"/>
  <img src="https://img.shields.io/badge/Twitter-blue?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter Badge"/>
</div>
[link](https://stackoverflow.com/questions/52099853/how-can-i-customize-my-readme-md-for-github)
##



#### Mixing HTML and Markdown
If you mix HTML with Markdown, Markdown stops processing once you enter raw HTML. To "end" that section, you just stop using HTML or insert a closing tag where necessary:

```markdown
<p>This is an HTML paragraph.</p>

Back to Markdown text.



```markdown
  ```bash
  python script.py --arg value
<br>
When rendered (e.g., on GitHub), users can manually copy the command, but there won't be a "copy" icon.

### 2. **Copy Button with HTML (Advanced)**
If you want to include a "copy" button, you can embed HTML and JavaScript for platforms that support it, like GitHub Pages or your documentation website.

```markdown
<pre>
<code>python script.py --arg value</code>
</pre>
<button onclick="navigator.clipboard.writeText('python script.py --arg value')">Copy</button>
