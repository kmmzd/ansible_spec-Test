# ansible_spec-Test
ansible_spec sample repository  
aqnsible_specを利用した、ansibleとserverspecのサンプルリポジトリです。

https://github.com/volanja/ansible_spec

# Directory structure
```
.
├── .ansiblespec                 
├── .rspec                       
├── README.md
├── hosts   
|   └── aws_ec2.yml 
├── playbook.yml                     
├── roles
|   ├── git/tasks
|   |   └── main.yml
|   ├── mysql/tasks
|   |   └── main.yml
|   ├── nginx/tasks
|   |   └── main.yml
|   ├── nodejs/tasks
|   |   └── main.yml
|   ├── ruby
|   |   ├── tasks
|   |   |   └── main.yml
|   |   └── templates
|   |       └── rbenv_system.sh.j2
|   └── spec
|       └── sample_spec.rb 
├── ansible.cfg
├── Rakefile                     
└── spec                         
    └── spec_helper.rb
 ```
