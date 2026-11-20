# Defensive Wireless Lab

## Overview
This repository documents an isolated wireless security lab designed to demonstrate the detection and mitigation of wireless threats specifically focusing on management frame vulnerabilities (such as deauthentication floods and Evil Twin attacks).

## Lab Architecture
* **Environment:** Closed, self-contained home lab network isolated from production traffic
* **Hardware & Capture:** Lenovo T420 running Linux with a wireless adapter in monitor mode
* **Analysis & SIEM:** Packet capture analysis (Wireshark/Tcpdump) paired with custom YAML/Sigma detection logic and Splunk log ingestion

## Detection Rules 
* 'y.yml' - Initial detection rule artifact for wireless management frame anomalies *( to be expanded with packet capture evidence and Splunk SPL queries)*
