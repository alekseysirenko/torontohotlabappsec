cd /home/dtu_training/.ansible/collections/ansible_collections/ace_box/ace_box/roles/app-webgoat/files/repo_latest/WebGoat/

java -Dserver.address=0.0.0.0 -jar webgoat-standalone/target/webgoat-standalone-7.1-exec.jar > /var/log/webgoat.log 2>&1 nohup &
