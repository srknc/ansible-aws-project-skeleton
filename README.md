# ansible-project-skeleton
This repository doesn't have any real code but only empty playbooks to show ansible repository file structure.  

** as a summary this repository manages only AWS infrastructure   

** it needs to ben run like;  

  ansible-playbook playbooks/main-infrastructure.yml --ask-vault-pass  

** all AWS infrastructure code are located under aws/ folder  

** all credentials should be kept at vars/credentials.yml (using ansible-vault)

** presentation about workflow can be found here;
http://www.slideshare.net/serkancapkan/aws-as-a-code-using-ansible-70242162
