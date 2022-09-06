# devops_task

Tree of project
```bash
devops_task/
└── ansible
    ├── playbook.yml - Pipeline trigger this playbook to run `setup_venvs` role
    └── roles
        └── setup_venvs 
            ├── files - requirements files
            │   ├── dev_venv.txt
            │   ├── hello_world.txt
            │   ├── prod_venv.txt
            │   └── test.txt
            ├── tasks
            │   └── main.yml
            └── vars 
                └── main.yaml
```
