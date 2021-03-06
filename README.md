# Malicious Encryption

This is the repository for my Senior Capstone research on ransomware.
- You can find the PDF of the paper in the main directory with the title *Ransomware__State_of_the_Field.pdf*
- The LaTeX source code can be accessed via *src/main.tex*

For this research, we were expected to write a paper on a topic of our choosing, covering the topic's history, technical aspects, and plausible future trends. The intention was to take a complicated topic and try to deliver it in a way that would take someone who knew nothing of the subject, and give them strong, basic understanding. I chose to research ransomware, specifically crypto-ransomware, because it was a topic that I knew almost nothing about at the time and I was beginning to develop an interest in the security side of computing. Ransomware had been a hot topic in the previous few years, and I wanted to see how this type of malware operated. I enjoyed the time I spent researching this topic, and I feel the knowledge I gained has given me a better understanding of how technologies can be leveraged in unique (sometimes malicious) ways.

## Technical Project
We also needed to complete a technical demonstration of our topic. I chose to create a very simple piece of ransomware using Python and the pycrypto library. It will only encrypt files starting in the Home directory of the current user, moving depth-first up into child directories. This was only tested on Debian-based Linux distributions, but it should work on any OS.

#### WARNING: Going through all steps and running this program *WILL* encrypt your files. You should be provided with the decryption key, but I cannot guarantee you will be able to recover your files. I suggest spinning up a VM and running it there. *Use at your own risk.*

Source code can be found here:
- https://github.com/cdalseth/techdemo

A video demonstrating the program can be found here:
- https://youtu.be/q7n0kfBVM6U
