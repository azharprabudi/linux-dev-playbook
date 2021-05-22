## Getting Started

### Requirements
1. Git
2. Linux brew

### Commands
<pre>
# Install dependencies
ansible-galaxy install -r requirements.yaml
ansible-galaxy collection install -r requirements.yaml

# Run ansible
ansible-playbook --connection=local -i 127.0.0.1, local.playbook.yaml --ask-become-pass
</pre>
