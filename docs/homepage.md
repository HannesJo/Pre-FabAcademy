# Setting up this Homepage

I decided to follow the recommendation from my supervisor and use *Markdown* as a base for my homepage. To learn the syntax I used this [guide](https://www.markdownguide.org/basic-syntax/). 

## Preparation
First it is required to set up [VSCode](https://code.visualstudio.com/) and [Python](https://www.python.org/). 

**Remeber to select "Add Python to PATH" during the installation of Python.**

Next, you need a [GitHub](https://github.com) Account and create a new repository there. 

Then I installed the Python Extension in VSCode under Extensions.

When in VSCode on the Welcome screen select **Clone Git Repository** and choose the repository GitHub. 

Next, the Markdown libraries need to be installed via the terminal. Material is a theme, that might be useful, but is not required.

```
pip install mkdocs

pip install mkdocs-material
```
## Creating a new webpage
Now it is time to create the basic files and directories needed for the webpage. 
```
mkdocs new .
```
The file structure is now visible in the Explorer and the file index.md is the frontpage. 

The file mkdocs.yml is used for some settings as defining the url, the theme and site title. 
```
site_name: My Pre-FabAcademy Hompeage
site_url: https://hannesjo.github.io/Pre-FabAcademy/
theme:
  name: material
```
