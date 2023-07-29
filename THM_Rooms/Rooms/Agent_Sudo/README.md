# Welcome to Agent Sudo Room in THM

Let's enable the OpenVPN and begin the room
<p align="center">
  <img src="TryHackMe/THM_Rooms/Rooms/Agent_Sudo/Image/01_Connect_openvpn.png" width="800" alt="Connect_openvpn"/> <br/>
<h6><i>Connect the OpenVpn in your terminal.</i></h6>
</p>

<p align="center">
  <img src="TryHackMe/THM_Rooms/Rooms/Agent_Sudo/Image/02_nmap_scan_IP.png" width="800" alt="nmap scan IP"/> <br/>
<h6><i>Scan the IP address using Nmap.</i></h6>
</p>

<p align="center">
  <img src="Agent_Sudo/Image/03_curl_IP.png" width="800" alt="curl IP"/> <br/>
<h6><i>Curl and IP address in your terminal and check.</i></h6>
</p>

<p align="center">
  <img src="Agent_Sudo/Image/04_curl_UserAgent.png" width="800" alt="curl UserAgent"/> <br/>
<h6><i>Curl and IP address in your terminal and check along the UserAgent.</i></h6>
</p>

<p align="center">
  <img src="Agent_Sudo/Image/05_Hydra_crack_ftp_&_download_files.png" width="800" alt="Hydra crack"/> <br/>
<h6><i>Using Hydra crack the FTP of the IP and download the available files.</i></h6>
</p>

<p align="center">
  <img src="Agent_Sudo/Image/06_viewing_file_FTP_.png" width="800" alt="view FTP-1"/> <br/>
<h6><i>Cat or read the To_agentJ.txt</i></h6>
</p>

<p align="center">
  <img src="Agent_Sudo/Image/06_viewing_file_FTP(1)_.png" width="800" alt="view FTP-2"/> <br/>
<h6><i>check the cutie.png file using string and found To_agentR.txt</i></h6>
</p>

<p align="center">
  <img src="Agent_Sudo/Image/07_unzip_file_.png" width="800" alt="unzip file"/> <br/>
<h6><i>Using binwalk extract the cutie.png and unzip the 8702.zip file.</i></h6>
</p>

<p align="center">
  <img src="Agent_Sudo/Image/08_cracking_password_john_.png" width="800" alt="crack password"/> <br/>
<h6><i>To crack the zip file, here we will use zip2john and obtain the hash and store it as zipjohn.txt then we will crack the password of that 8702.zip file using zipjohn.txt using john the ripper. </i></h6>
</p>

<p align="center">
  <img src="Agent_Sudo/Image/09_cracking_random_word_with_base64(1)_.png" width="800" alt="cracking random word with base64"/> <br/>
<h6><i>crack the random word "QXJlYTUx" with base64.</i></h6>
</p>

<p align="center">
  <img src="Agent_Sudo/Image/09_cracking_random_word_with_base64(2)_.png" width="800" alt="cracking random word with base64-1"/> <br/>
<h6><i>Now we can read the message of Agent R to Agent C.</i></h6>
</p>

<p align="center">
  <img src="Agent_Sudo/Image/10_checkother_file_using_strings_.png" width="800" alt="check other file using strings"/> <br/>
<h6><i>check the cute-alien.jpg file using strings to get any valid information.</i></h6>
</p>

<p align="center">
  <img src="Agent_Sudo/Image/11_steghide_enter_Area51password_cat_message_.png" width="800" alt="steghide"/> <br/>
<h6><i>Use steghide to extract the file cute-alien.jpg with the password we obtain "crack the random word "QXJlYTUx" with base64".</i></h6>
</p>

<p align="center">
  <img src="Agent_Sudo/Image/12_get_the_flag_with_jamesSSH_.png" width="800" alt="jamesSSH"/> <br/>
<h6><i>Connect to SSH with james ID and obtain the flag.</i></h6>
</p>

<p align="center">
  <img src="Agent_Sudo/Image/13_download_SSH_Alien_autopsy_file_.png" width="800" alt="download SSH Alien autopsy file"/> <br/>
<h6><i>Download the Alien_autospy.jpg in SSH of james.</i></h6>
</p>

<p align="center">
  <img src="Agent_Sudo/Image/14_CVE_Vuln_.png" width="800" alt="CVE Vuln"/> <br/>
<h6><i>CVE vulnerability for "(ALL, !root) /bin/bash" exploit.</i></h6>
</p>

<p align="center">
  <img src="Agent_Sudo/Image/14_Verify_the_file_name_.png" width="800" alt="Verify the file"/> <br/>
<h6><i>Verify the Alien_autospy.jpg file using exiftool and OSINT about the image to get the file's full name.</i></h6>
</p>

<p align="center">
  <img src="Agent_Sudo/Image/15_cat_the_roottxt_.png" width="800" alt="roottxt"/> <br/>
<h6><i>Use the exploit previously mentioned and access the root, then cat the root.txt to get the flag.</i></h6>
</p>
