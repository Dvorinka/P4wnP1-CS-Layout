### **Czech** Keyboard mapping for the P4wnP1 A.L.O.A. tool!
(https://github.com/RoganDawes/P4wnP1_aloa)

### Installation
<ol>
  <li>SSH into your Raspberry Pi Zero W(H)</li>
  <li>For the password enter toor.</li>
  <li>Use the ls command to see the directories.</li>
  <li>Then cd into the P4wnP1 directory.</li>
  <li>After that you need to cd into the dist directory.</li>
  <li>Then you have to cd inside the keymaps directory.</li>
  <li>Finally you can just clone my CS layout with the commands bellow.</li>
</ol>

#Commands
1.SSH:<br>
  `ssh root@172.16.0.1`<br>
2.PASSWORD:<br>
  `toor`<br>
3. SHOW ALL DIRECTORIES:<br>
  `ls`<br>
4. MOVE INTO THE P4WNP1 DIRECTORY:<br>
  `cd P4wnP1`<br>
5. MOVE INTO THE DIST DIRECTORY:<br>
  `cd dist`<br>
6. MOVE INTO THE KEYMAPS DIRECTORY:<br>
  `cd keymaps`<br>
7. FIND OUT THE WHOLE DIRECTORY PATH:<br>
  `pwd` <br>
  Copy it!<br>
8. NOW COPY THIS DIRECTORY WITH GIT:<br>
  `git clone https://github.com/Dvorinka/P4wnP1-CS-Layout.git`<br>
9. GO TO YOU WINDOWS MACHINE (I tested only windows): <br>
  Open Powershell in the directory that you downloaded and type this command: <br>
  `scp CS.json root@172.16.0.1:/P4wnP1/dist/keymaps`<br>
  Enter the password again:
  `toor`
