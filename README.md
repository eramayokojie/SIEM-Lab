<h1>Failed RDP to IP Geolocation Information</h1>


<h2>Description</h2>
<b>The Powershell script in this repository is responsible for parsing out Windows Event Log information for failed RDP attacks and using a third party API to collect geographic information about the attackers location.
</b>
<br />
<br />
The script is used in this demo where I setup Azure Sentinel (SIEM) and connect it to a live virtual machine acting as a honey pot.
We will observe live attacks (RDP Brute Force) from all around the world. I will use a custom PowerShell script to
look up the attackers Geolocation information and plot it on an Azure Sentinel Map!
<br />
<br />


<h2>Languages Used</h2>

- <b>PowerShell:</b> Extract RDP failed logon logs from Windows Event Viewer 

<h2>Utilities Used</h2>

- <b>ipgeolocation.io:</b> IP Address to Geolocation API

<h2>Script used to gather custom geodata from attackers</h2>

<img width="1245" alt="Screenshot 2024-02-05 at 10 58 18 PM" src="https://github.com/eramayokojie/SIEM-Lab/assets/153569453/77fa9cee-3458-4829-a6f0-1e5ed4c8fd5a">

<h2>World map of incoming attacks after 24 hours (built custom logs including geodata)</h2>

<img width="951" alt="Screenshot 2024-02-05 at 11 03 18 PM" src="https://github.com/eramayokojie/SIEM-Lab/assets/153569453/7738ca57-8e96-4ec5-9bfd-5c957a2e350e">
