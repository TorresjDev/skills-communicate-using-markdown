<<<<<<< HEAD
<!--
  <<< Author notes: Step 3 >>>
  Start this step by acknowledging the previous step.
  Define terms and link to docs.github.com.
-->

## Step 3: Add a code example

_Great job adding an image to the file :tada:_

Let's add some code blocks. Code blocks can render differently depending on the language.

### Example 1

<pre>
```
$ git init
Initialized empty Git repository in /Users/skills/Projects/recipe-repository/.git/
```
</pre>

#### How it looks

```
$ git init
Initialized empty Git repository in /Users/skills/Projects/recipe-repository/.git/
```

### Example 2

<pre>
``` javascript
var myVar = "Hello, world!";
```
</pre>

#### How it looks

```javascript
=======
## Step 3: Add a code sample

Let's learn about [code blocks](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#quoting-code) and [syntax highlighting](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/creating-and-highlighting-code-blocks) based on the language.

> [!TIP]
> Many programming languages are supported. Try testing out some other file extension types!

### Example: Terminal Command

````md
```bash
git clone https://github.com/skills/communicate-using-markdown
```
````

```bash
git clone https://github.com/skills/communicate-using-markdown
```

### Example: Javascript Code

````md
```js
var myVar = "Hello, world!";
```
````

```js
>>>>>>> upstream/HEAD
var myVar = "Hello, world!";
```

### :keyboard: Activity: Adding a code example

<<<<<<< HEAD
1. As you did before, edit the file in this pull request.
1. In the file, add the correct Markdown for a code example of your choice.
1. Use the **Preview** tab to check your Markdown formatting.
1. Commit your changes.
1. Wait about 20 seconds then refresh this page (the one you're following instructions from). [GitHub Actions](https://docs.github.com/en/actions) will automatically update to the next step.
=======
1. On the `start-blog` branch, open the `day-1.md` file for editing.

1. Below **Review** level two heading add the following entry recording an awesome code snippet you just learned from the GitHub Blog.

   ````md
   Convert an image or video from dark mode to light mode using [ffmpeg](https://www.ffmpeg.org)

   ```bash
   ffmpeg -i input.mp4 -vf "negate,hue=h=180,eq=contrast=1.2:saturation=1.1" output.mp4
   ```
   ````

1. Use the **Preview** tab to check your Markdown formatting.

1. In the top right, click the **Commit changes** button and commit directly to the `start-blog` branch.

1. With our code block committed, Mona should be busy reviewing your work and preparing the next steps.

<details>
<summary>Having trouble? 🤷</summary><br/>

- Confirm you are editing the correct file and branch.
- Double check your syntax. A code block is three backticks ` ``` ` not three apostrophes `'''`

</details>
>>>>>>> upstream/HEAD
