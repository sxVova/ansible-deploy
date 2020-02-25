# Playbook for *DEMO3*

These **playbooks** can automatically deploy the necessary *infrastructure*.  
**Flask playbook** pulls the application *image* onto the machine and launches it.  
**Sentry playbook** sets *Sentry* and creates a *superuser*.  
For correct work of **sentry playbook** when building the image, you need to delete [27-38] lines from the   **src/sentry/receivers/users.py** file. 
