As a DevOps Engineer,
I want to create an Ansible playbook with a role to automatically deploy a web server in a container,
So that I can ensure a consistent, repeatable, and testable deployment process for our web applications.

Acceptance Criteria
AC1: Ansible Role for Web Server. An Ansible role must be created to handle the web server setup. This role should be responsible for all tasks related to the web server's configuration.

AC2: Containerized Deployment. The Ansible playbook must target a containerized environment (e.g., Docker or Podman). The playbook should be able to start the container and deploy the web server inside it.

AC3: Web Page Deployment. The playbook must deploy a simple index.html web page onto the web server.

AC4: Reachability Test. The playbook must include a task that tests if the deployed web page is reachable from the local machine or another specified host. This can be a simple curl or uri module task that checks for a 200 OK status.

AC5: GitHub Action for Linting. A GitHub Action workflow must be set up in the repository. This workflow must trigger on every push and pull request to the main branch and run ansible-lint against the playbook to enforce code quality and best practices.

AC6: Successful Playbook Execution. The entire Ansible playbook must run successfully from start to finish without any errors.

AC7: Documentation. The README.md file in the repository should be updated to explain how to run the playbook and what its purpose is.
