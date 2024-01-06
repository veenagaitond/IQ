1.	What all things have you done on Ansible?
•	I'm a text-based AI model and don't have personal experiences, but I can provide information and answer questions about Ansible.
2.	2 Roles in Ansible?
•	Ansible roles are reusable, self-contained units of playbooks. Examples of roles could be a web server role and a database server role.
3.	How do you call a handler in a task?
•	You can call a handler in a task using the notify keyword. When a task triggers a handler, Ansible will run the specified handler.
4.	What is Ansible registry?
•	There is no specific Ansible registry. It might be a typo or a misunderstanding. If you meant "register," it is used to capture the output of a task and use it later in the playbook.
5.	How to use the with_items command to run a loop in Ansible?
•	with_items is deprecated, and you should use loop instead. Example:
yamlCopy code
- name: Loop example debug: msg: "{{ item }}" loop: - item1 - item2 
6.	Ansible playbook?
•	An Ansible playbook is a YAML file containing a set of plays. Each play represents a set of tasks to be executed on a set of hosts.
7.	Role in Ansible?
•	An Ansible role is a way of organizing playbooks and related files to make them reusable and shareable.
8.	About Ansible commands?
•	Ansible commands are used to perform various tasks like running playbooks, managing inventory, and executing ad-hoc commands.
9.	How do playbooks work in Ansible?
•	Playbooks in Ansible define a set of tasks to be executed on one or more hosts. They are written in YAML and are executed sequentially.
10.	How to maintain inventory in Ansible?
•	Ansible inventory is typically maintained in INI or YAML format. It defines hosts and groups that Ansible can manage.
11.	Explain Ansible Ad-Hoc Commands?
•	Ad-hoc commands are quick, one-line commands used for tasks like pinging hosts or running simple commands without creating a playbook.
12.	Write a playbook and explain it?
•	I'll provide a simple example:
yamlCopy code
13.	- name: Example Playbook
14.	  hosts: web_servers
15.	  tasks:
16.	    - name: Ensure Apache is installed
17.	      package:
18.	        name: apache2
19.	        state: present
20.	What is an Ansible role?
•	Ansible roles are a way to group multiple tasks, variables, and handlers into a reusable and shareable structure.
21.	Types of inventory in Ansible?
•	INI and YAML are common formats for Ansible inventory. Dynamic inventories can also be generated from external sources.
22.	How do you call a playbook inside another playbook?
•	You can use the import_playbook or include_playbook directives to include one playbook inside another.
23.	Tasks, image or file name (YAML), notify handlers?
•	This seems to be a mix of terms. Tasks are actions performed in a playbook, and YAML is the format for writing Ansible playbooks. Handlers are special tasks triggered by events.
24.	Use case scenarios for Ansible in your project?
•	Use cases depend on the project but could include server configuration, application deployment, and automation of various IT processes.
25.	Command to ping a server in Ansible?
•	ansible all -m ping
26.	What kind of work do you configure, and why do you prefer Ansible?
•	Ansible is preferred for its simplicity and agentless architecture. It is commonly used for configuration management, application deployment, and automation.
27.	Difference between Chef & Ansible?
•	Both are configuration management tools. Chef uses a client-server model, requires an agent on nodes, and uses Ruby. Ansible is agentless, uses SSH, and is based on YAML.
28.	One reason to use Chef instead of Ansible?
•	If your organization has a strong Ruby background, Chef might be preferred due to its use of Ruby for configuration.
29.	Ansible Galaxy and Ansible Tower?
•	Ansible Galaxy is a platform for sharing and discovering Ansible roles. Ansible Tower is a web-based UI and automation platform for Ansible.
30.	Have you worked on Ansible?
•	I don't work on anything myself, but I can help answer questions and provide information on Ansible.
31.	Explain Playbook?
•	Ansible playbooks are YAML files that define a set of tasks to be executed on hosts. They are the main building blocks of Ansible automation.
32.	Roles in Ansible?
•	Ansible roles are a way to organize and reuse tasks, handlers, and variables in a structured format.
33.	Ansible Tower?
•	Ansible Tower is a web-based UI and automation platform for Ansible. It provides a dashboard, role-based access control, and job scheduling.
34.	Ansible Playbook?
•	See answer #6.
35.	Ansible Role?
•	See answer #7.
36.	Types of Inventory?
•	INI and YAML are common types of inventory files in Ansible.
37.	Ansible questions: Inventory file, playbook architecture?
•	Inventory files list hosts, and playbooks define tasks to be executed on those hosts. Playbooks are structured with plays containing tasks.
38.	How are you using Ansible in your project?
•	I don't personally use Ansible, but it's commonly used for automation and configuration management in IT projects.
39.	On how many servers using Ansible have you done configuration?
•	I don't perform configurations, but Ansible can be used to configure any number of servers.
40.	What do you know about Ansible?
•	Ansible is an open-source automation tool used for configuration management, application deployment, task automation, and orchestration.
41.	How to copy the output of one playbook as input to another playbook?
•	You can use the register keyword in a task to capture the output and then use it in subsequent tasks or playbooks.
42.	How to include 2, 4, 6 tasks of one playbook in another playbook?
•	You can use the include_tasks or import_tasks directives to include specific tasks from one playbook into another.
43.	If I have 2 Ansible roles, how will I copy the output of one role to another role?
•	Roles are designed to be independent. To share data, use variables or leverage the import_role or include_role directives in your playbook.
44.	Handlers in Ansible?
•	Handlers are tasks that only run when notified by other tasks. They are often used to restart services after a configuration change.
45.	Explain how you set up Ansible?
•	To set up Ansible, install it on a control node, define an inventory file, and create playbooks with tasks to be executed on remote hosts.
46.	Which extension do Ansible plugins have?
•	Ansible plugins have various extensions depending on their type, such as .py for Python plugins or .sh for shell script plugins.
47.	Explain Playbook?
•	See answer #6.
48.	Roles in Ansible?
•	See answer #7.
49.	Write an Ansible playbook for service and install modules?
•	Here's a simple example:
yamlCopy code
50.	- name: Example Playbook
51.	  hosts: web_servers
52.	  tasks:
53.	    - name: Ensure Apache is installed
54.	      package:
55.	        name: apache2
56.	        state: present
57.	    - name: Ensure Apache is running
58.	      service:
59.	        name: apache2
60.	        state: started
61.	How to copy files from remote to local in Ansible?
•	You can use the fetch module to copy files from remote to local. Example:
yamlCopy code
-- name: Fetch file from remote to local
  fetch:
    src: /path/to/remote/file.txt
    dest: /path/to/local/

