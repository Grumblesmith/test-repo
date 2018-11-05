# Upgrading the Agent



1. Stop the Linux Agent \(use the appropriate command for your distro\). The most common being:
   * `service netuitive-agent stop`
   * `/etc/init.d/netuitive-agent stop`
   * `initctl stop netuitive-agent`
   * `systemctl stop netuitive-agent`
2. Run the update command for your distro: 
   * `yum -y update netuitive-agent`
   * `apt-get update netuitive-agent`
   * `apt-get install --only-upgrade netuitive-agent`  


     If you have not customized the Netuitive configuration file in any way \(other than inputting the API key\), jump to step 6. If you’ve customized the configuration file, continue on.
3.  Get the difference between the old configuration file \(**netuitive-agent.conf**\) and the new configuration file \(**netuitive-agent.conf.rpmnew**\): `diff -u /opt/netuitive-agent/conf/netuitive-agent.conf.rpmnew /opt/netuitiveagent/conf/netuitive-agent.conf`
4. Copy your changes from the old file to new file.
5. Rename the old file to **netuitive-agent.conf.old** and the new configuration file to **netuitive-agent.conf**.
6. Start the Linux Agent. The most common commands being: 
   * `service netuitive-agent start`
   * `/etc/init.d/netuitive-agent start`
   * `initctl start netuitive-agent`
   * `systemctl start netuitive-agent`

