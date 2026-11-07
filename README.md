This is a collection of playbooks I use to apply roles from the [ansible-roles](https://github.com/Zeashh/ansible-roles) project.

Just as that project, it is highly opinionated, and sanitized for public access.

If you decide to use these, look at the [ansible-roles](https://github.com/Zeashh/ansible-roles) project and consider its limitations. The limits of these playbooks are directly tied to the limits of those roles.


| Path                           | Explanation                                 |
| ------------------------------ | ------------------------------------------- |
| `collections/`, `requirements.txt`, `requirements.yml` | Dependencies                                | 
| `inventory-sample/`              | Sample inventory, write your own into `inventory/` |
| `templates-sample/`              | Sample template overrides, write your own into `templates/`
| `files-sample/`              | Sample file overrides, write your own into `files/`
| `inventory/`                     | Global inventory used by all playbooks      |
| `templates/`                     | Templates used by playbooks                 |
| `files/`                         | Files used by playbooks                     |
