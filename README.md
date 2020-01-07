- Installation

Unzip jboss zip file

unzip jboss-eap-7.1.0.zip

Create an admin user

./bin/add-user.sh

- Running JBoss EAP 

Running standalone mode

./bin/standalone.sh

Running domain mode

./bin/domain.sh

Run another host controller

./bin/domain.sh --host-config=host-slave.xml -Djboss.socket.binding.port-offset=100 -Djboss.domain.master.address=127.0.0.1 -Djboss.management.native.port=10099 -Djboss.management.http.port=10090 -Djboss.management.https.port=10443


- Show Directory structure

- Show Java configuration

- Show Manage console

- Show Deploys

- Show Resources configuration 

- Show Users management

- Show Certificates management

- Show Logs
