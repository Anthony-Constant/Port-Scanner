<!DOCTYPE html>
<html>
<head>
</head>
<body>
	<h1>Port_Scanner.py</h1>
	<p>A Python script to scan a target IP address and determine which ports are open.</p>
	<h2>How to use</h2>
	<ul>
		<li>Enter the target IP address when prompted.</li>
		<li>The script will automatically scan all 1000 ports and determine which ones are open on the target machine.</li>
		<li>Once the scan is complete, the script will print "Port Scan Complete!" in the terminal.</li>
		<li>The script will also create and write to a "port_logs.txt" file on your local machine, which will contain all open ports found during the scan.</li>
	</ul>
	<h2>References</h2>
	<ul>
		<li><a href="https://docs.python.org/3/library/concurrent.futures.html">Python documentation on concurrent.futures</a></li>
		<li><a href="https://en.wikibooks.org/wiki/Python_Programming/Threading#:~:text=Threading%20in%20python%20is%20used,calls)%20at%20the%20same%20time.&text=Threading%20allows%20python%20to%20execute,simulated%20with%20the%20sleep%20function.">Python Programming/Threading</a></li>
		<li><a href="https://docs.python.org/3/library/socket.html">Python documentation on socket</a></li>
		<li><a href="https://www.paloaltonetworks.com/cyberpedia/what-is-a-port-scan">Palo Alto Networks Cyberpedia: Port Scan</a></li>
	</ul>
	<h2>Credits</h2>
	<p>This script was created by Anthony Constant (AC). If you have any questions or suggestions, you can contact him at <a href="https://www.anthonyconstant.co.uk/">anthonyconstant.co.uk</a>.</p>
	<h2>License</h2>
	<p>This script is released under the MIT License. See the LICENSE file for more details.</p>
</body>
</html>
