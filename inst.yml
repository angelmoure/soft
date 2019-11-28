- name: install packages on a fresh Ubuntu
  hosts: all
   
  tasks:
    - name: install all packages
      apt: 
        pkg: 
        - vlc
        - audacity
        - inkscape
      become: yes
      become_method: su
     
