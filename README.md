# TSM_Firewall_portal


https://sites.google.com/site/klaaspublic/rhcsarhce/rhce-voorbeeld-examens/rhcsarhce-practice-exams-with-virtual-machines/rhce-practice-exam-1/rhce-practice-exams-1---uitwerkingen


http://www.everybodyhertz.co.uk/rhce-sample-exam/
http://www.dbspecialists.com/scripts/
http://mrafeyblog.blogspot.fr/2013/02/compare-two-oracle-users-privilege-and.html
http://ptgmedia.pearsoncmg.com/images/9780789754059/samplepages/9780789754059.pdf
http://nothen.com.ar/en/how-to-practice-for-red-hats-ex200-and-ex300-exams/
http://balajitheone.blogspot.fr/2011/02/red-hat-ex300-objectives-and-solutions.html
https://www.digitalocean.com/community/tutorials/how-to-install-elasticsearch-logstash-and-kibana-elk-stack-on-ubuntu-14-04
https://github.com/texastwister/OpenRHCE
https://unixspace.wordpress.com/2013/08/09/rhcsa-rhce-exams-how-to-prepare-the-labs/comment-page-1/
http://www.lestutosdenico.com/divers/les-certifications-en-securite-de-l-information
*----------------------------------------------------------------------------------------------------------------*
                                       RHCE Sample Exam 1                                                         
*----------------------------------------------------------------------------------------------------------------*
You’ll have two hours to complete the following tasks:1.
 
Configure an SSH server with access limited to the local network. Create local usersnamed katie and dickens. Limit SSH access on that server only to user katie.2.
 
Configure a Samba server. Share a directory named /food with user dickens. Share asecond directory named /book limited to users tim and stephanie.3.
 
Set up a vsFTP server with access limited to the server1.example.com and the physicalhost system.4.
 
Set up a local NTP server, accessible to the local network.5.
 
Configure an NFS server to share the /home directory only with the physical host system.6.
 
Configure Apache with two secure web sites on the same virtual server. Call those websites shost1.example.com and shost2.example.com. Create and configure an appropriateSSL key for those web sites.7.
 
Configure a local caching nameserver, and set up the local system to use that nameserver.8.
 
Create a script that backs up all files from the /home directory on a daily basis.9.
 
Create an RPM from a single file. Use the README file in the/usr/share/doc/tcp_wrappers-7.6 directory. Set up the RPM with a package name of tcpwrapdoc, version 1.0. When installed, it should write the README file to the/opt/tcpwrap directory.10.
 
Configure IPv4 and IPv6 forwarding on the local system.11.
 
Set up system activity reports to run the related accounting tool every five minutes.
*----------------------------------------------------------------------------------------------------------------*
                                       RHCE Sample Exam 2                                                         
*----------------------------------------------------------------------------------------------------------------*
You’ll have two hours to complete the following tasks:1.
 
Configure the server1.example.com system as a logging server. Configure thetester1.example.com system (or the physical host system) as a logging client.2.
 
Configure the server1.example.com system as a Kerberos client on the example.comdomain, with a KDC and administrative server of the physical host system.3.
 
Set up an Apache web server with two regular virtual hosts. Set it up on URLstest1.example.com and test2.example.com. Create and use the /web subdirectory for this purpose. Include appropriate index.html files, with contents for each URL.4.
 
Set up a shared subdirectory named cubs on that Apache web server, accessible to userselizabeth and fred. Limit access to the local network.5.
 
Configure the system to work with a CGI application, accessible on thetest1.example.com system. For that purpose, you may use the following code in anappropriate CGI script. Call it the good.pl file.

"#!/usr/bin/perlprint "Content-type: text/html\n\n";print "Good Job!\n";"

6.
 
Set up an FTP server that supports only anonymous access, even from outside your LAN.Do not allow access from any regular users, even if the ftp_home_dir boolean is on.7.
 
Configure a caching-only DNS server that forwards requests to the physical host system.8.
 
Set up a local SMTP server that supports access limited to systems on the local network.9.
 
Configure an SSH server for user mike on the server1.example.com system. Configure password-free access, with passphrases, using key-based authentication from a remotesystem, either tester1.example.com or the physical host. Use the following passphrase:
Linux rocks, Windows does not.
10.
 
Set up masquerading from the network with server1.example.com to outside networks,using the IP address of the physical host system.
