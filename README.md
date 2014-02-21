OA_scripts
==========

OpenAudit Scripts

This is a repository to the OpenAudit's audit_linux.sh script.
The starter goal was to fix the script to work completely fine on a wider variety of Linux Systems.

Now it will receive scripts to audit other platforms.

RoadMap

6- Adjust details to publish and publish. Try to contact Opmantek to submit the fix (officially). (done)
            Now the script is official now. (http://www.open-audit.org/downloads.php)

5- Fix the chkconfig problem. (done)

4- Analyse why chkconfig messages show on output (done)

3- Test on CentOS 5 and 6 (done)

2- If not a bug, fix network card's data gathering to CentOS 5 (It works fine on CentOS 6)
Because of the absence of some symlink on /sys/class/net/*/device
More broader strategy found on http://www.linuxfromscratch.org/blfs/view/development/chapter07/network.html. (done)

1- Analyse if is a bug in a instalation or a characteristic of the CentOS 5. (done)





