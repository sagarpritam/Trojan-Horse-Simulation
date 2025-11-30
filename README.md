# Trojan Horse Simulation

This project is a comprehensive simulation of a Trojan horse malware, created for cybersecurity learning and analysis within a secure virtual environment. It replicates common malicious behaviors such as:

🔹 Keylogging

Implements keyboard event hooks to capture keystrokes and store them locally, showcasing how attackers steal sensitive information.

🔹 DLL Injection

Demonstrates process hijacking through simulated DLL injection using Windows APIs like `VirtualAllocEx`, `WriteProcessMemory`, and `CreateRemoteThread`. A dummy DLL is used to ensure safety.

🔹 Reverse Shell Simulation

Creates a local-only reverse shell environment, enabling command execution to mimic post-exploitation scenarios without any external network communication.

🔍 Detection & Analysis

The project includes full detection workflows using:

* Sysmon  for system activity logging
* Process Explorer  to inspect injected DLLs
* Wireshark for local traffic analysis
* Windows Defender to observe malware behavioral alerts

These tools help visualize how modern security solutions detect malicious operations.

🎯 Purpose & Outcome

This simulation provides hands-on experience with both offensive malware techniques and defensive detection strategies. It is ideal for professionals preparing for **VAPT**, **SOC**, **Incident Response**, and **Malware Analysis** roles.

