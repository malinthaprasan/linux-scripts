# linux-scripts
Day to day useful bash scripts

Configuration:

Add following entry to /etc/profile

PATH=location-of-linux-script-folder:$PATH


Usage:

Example:

run "mci" in a maven project home folder to "mvn clean install"

mci : mvn clean install
mcinotests : mvn clean install -Dmaven.test.skip=true
showcarbonpids : show running wso2 instantances' pids
