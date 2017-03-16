Selenium
=========

Role to install headless Selenium web driver.

Requirements
------------

None.

Role Variables
--------------

```yml
username:       vagrant
group_name:     '{{ username }}'
user_home_path: '/home/{{ username }}'
```

Dependencies
------------

```
bearandgiraffe.base
bearandgiraffe.java8
```

Example Playbook
----------------

```yml
- hosts: servers
  roles:
    - { role: bearandgiraffe.selenium }
```

License
-------

The Unlicense (see LICENSE)

Author Information
------------------

Youssef Chaker (@ychaker) from Bear & Giraffe LLC (@bearandgiraffe).
