# Paxos Lab - Workshop 3: Understanding and Stress-Testing Paxos

**Course:** Fundamentals of System Security (COMSM0122)  
**Workshop:** Workshop 3 - Understanding and Stress-Testing Paxos  
**Date:** [Insert Workshop Date Here, 21, 10, 2026]  
**Author:** [Pengfei Zheng/ 2906205]

## 📖 Project Overview
This repository contains a simplified JavaScript-based Paxos simulator designed for educational and experimental purposes. It models a distributed system containing proposers, acceptors, learners, quorums, proposal numbers, and message exchanges. 

The goal of this lab is to observe, modify, and experiment with the Paxos consensus algorithm to understand how distributed systems preserve a single agreed decision despite crashes, node failures, network partitions, and competing proposers.

## 📂 Directory Structure
- `simulator.js`: Core Paxos protocol implementation (Consensus Engine).
- `proposal.js`: Represents a Paxos proposal (number + value).
- `proposer.js`: Initiates consensus, creates proposals, and coordinates agreement.
- `acceptor.js`: Issues promises, accepts proposals, and remembers history.
- `learner.js`: Learns and records the final chosen decision.
- `quorum.js`: Calculates majority size and verifies quorum formation.
- `network.js`: Simulates message delivery, loss, and network partitions.
- `scenarios/`: Contains predefined scenarios for guided exercises.

## 🛠️ Prerequisites
- [Node.js](https://nodejs.org/) (version 18 or newer)
- A code editor such as Visual Studio Code
- Basic familiarity with JavaScript

## 🚀 Installation & Setup
1. Clone this repository or download the source code.
2. Open the folder in your terminal or VS Code.
3. Install the required dependencies:
   ```bash
   npm install# Paxos
