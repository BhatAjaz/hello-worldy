## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/ajaz706/hello-worldy/edit/main/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

<form><br>
Enter your First Name: <input type="text" id="firstname"/><br><br>
Enter your Last Name: <input type="text" id="lastname"/><br><br>
<input type="submit" value="Submit" onclick="formdata()"/><br>
</form>

<script>
function formdata() 
{
var firstname1= document.getElementById("firstname").value;
var lastname1= document.getElementById("lastname").value;
document.writeln("<h1>Confirmation Page</h1><br>");
document.writeln("Thank you for completing this form.<br><br>");
document.writeln("The first name you entered is " + firstname + "<br>");
document.writeln("The last name you entered is " + lastname);
}
</script>


### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```


For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/ajaz706/hello-worldy/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
