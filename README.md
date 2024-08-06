# ansible-dse

## Description
This is an Ansible Automation Platform playbook to deploy DataStax Enterprise 6.8 using VM deployed by VMWare Aria Automation. It was designed to work in conjunction with our sample Aria Assembler Blueprint.

This playbook was created for demonstration purposes and should serve as a basis to create a more comprehensive playbook. 


## Playbook Structure

```
ansible-dse
├── collections
│   └── requirements.yml
├── roles
│   ├── ansible_role_configure_os
│   │   └── ...
│   └── ansible_role_dse
│       └── ...
├── deploy.yml
├── LICENSE
└── README.md
```

- `collections/`: directory containing the module requirements for the playbook.
- `roles/`: directory containing the roles.
- `deploy.yml`: the playbook file.
- `LICENSE`: project license.
- `README.md`: instructions and links related to this playbook.
