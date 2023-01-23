---
share: true
---

### Github
- Create a new repository from [mkdocs template](https://github.com/ObsidianPublisher/publisher-template-gh-pages/generate)
- Git clone https://github.com/username/repo-name
- Configuration
	- under Settings for Pages on "Build and Deployment", choose `Github Actions`
	- under Settings for Actions on "Workflow Permission", checked `Read and Write Permission` and `Allow Github actions to approve pull requests`

### Obsidian
- Open vault as folder to the repo
- Install the Github Publisher plugin
- Configuration
	- Repo Name
	- User Name
	- Token
	- Branch
- Other settings
	- Attachment folder: `docs/assets/img`
	- Folder behaviour: `obsidian path`
	- Default folder: `docs`
	- Transfer attachment: `enabled`
	- Share through file menu: `enabled`
	- Auto clean up: `enabled`

### Frontmatter

`Share: true` to set note to push to Github

### Mkdocs.yml

Navigation
Use `nav` to create sections in a page

```
nav: 
  - 'home':
	  - 'Overview': 'index.md'
	  - 'Notes': 'notes.md'
  - 'Support':
	  -  'Callouts': 'callouts.md'
	  -  'Table': 'table.md'
```
  
1.  `site_name`
2.  `site_description`
3.  `site_url`: `https://github_username.io/repo_name`