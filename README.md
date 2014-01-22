
    ansible-playbook -i inventory.yml test-playbooks.yml
    >> ok: [node2] => {
           "msg": "default"
       }

    ansible-playbook -i inventory.yml test-playbooks.yml --extra-vars="message=hello"
    >> ok: [node2] => {
           "msg": "hello"
       }

