# Tarini.apk


# 🌐 Disaster Communication & Response Network

### *When infrastructure fails, the network becomes the infrastructure.*

A decentralized disaster-response system designed to keep critical information flowing when **cellular networks and Internet infrastructure are unavailable**.

```text
📱 Mesh → 📡 LoRa → 🧠 AI → 🚑 Rescue Center
                  ↓
          🔎 Future Subsurface Link
```

---

## 🚨 Problem

Natural disasters can destroy communication infrastructure and isolate survivors, especially those trapped beneath collapsed structures.

Our goal is to create an alternative communication path:

```text
👤 Survivor → 📱 Mesh → 📡 LoRa → 🧠 AI → 🚑 Rescue
```

---

## 🏗️ Architecture

```text
                    🚑 Rescue Center
                           ▲
                      🧠 AI Layer
                           ▲
                         📡 LoRa
                           ▲
              📱 ↔ 📱 ↔ 📱 ↔ 📱
                   Surface Mesh
                           ▲
                  🔎 Future Layer
                           ▲
                    👤 Survivor
```

### 📱 1. Surface Mesh

Android devices communicate directly and act as relay nodes.

* Offline device discovery
* Peer-to-peer communication
* Multi-hop routing
* SOS & location sharing
* Store-and-forward
* TTL & duplicate prevention
* Battery/signal-aware routing

### 📡 2. LoRa Backbone

ESP32 + LoRa nodes connect the surface mesh to the rescue center.

```text
📱 → 📱 → 📱 → 📡 LoRa → 🚑
```

Provides long-range backhaul without relying on cellular infrastructure.

### 🧠 3. AI Intelligence

AI operates on network and emergency data to assist with:

* 🚨 Emergency prioritization
* 🧠 Intelligent routing
* 📡 Network-failure prediction
* 🗺️ Rescue & resource recommendations

### 🔎 4. Subsurface Communication

A future research layer for connecting survivors trapped beneath rubble to the surface network.

Potential approaches:

* Specialized RF
* Acoustic/vibration communication
* Deployable relay nodes
* Hybrid approaches

**Penetration and reliability will be experimentally evaluated rather than assumed.**

---

## 💬 Message Protocol

Messages contain structured information such as:

```text
Message ID
Sender ID
Message Type
Timestamp
Priority
TTL
Location
Payload
```

Possible message types:

```text
SOS
TEXT
LOCATION
MEDICAL
NODE_STATUS
DETECTION
ACKNOWLEDGEMENT
```

---

## 🧠 Routing

Routing decisions can consider:

```text
Signal Strength
Battery Level
Distance
Connection Stability
Node Connectivity
Network Congestion
```

The project will compare:

**Traditional/Flooding vs Rule-Based vs AI-Assisted Routing**

---

## 🧪 Evaluation

| Metric                 | Purpose                 |
| ---------------------- | ----------------------- |
| Packet Delivery        | Reliability             |
| Latency                | Response speed          |
| Hop Count              | Routing efficiency      |
| Packet Loss            | Network quality         |
| Battery Usage          | Node lifetime           |
| Recovery Time          | Fault tolerance         |
| LoRa Range             | Backhaul capability     |
| AI Improvement         | Routing efficiency      |
| Subsurface Reliability | Experimental capability |

---

## 🛠️ Technology Stack

**Software**

* Kotlin
* Android
* Offline local storage
* Custom communication protocol
* Python / ML for AI

**Hardware**

* ESP32
* LoRa modules
* GPS
* Battery-powered relay nodes

**Rescue System**

* Web/Laptop dashboard
* Network visualization
* AI decision-support engine

---

## 🚧 Development Roadmap

```text
1. 📱 Android Mesh
      ↓
2. 🔗 Multi-Hop + Store-and-Forward
      ↓
3. 📍 SOS + Location
      ↓
4. 📡 ESP32 + LoRa
      ↓
5. 🚑 Rescue Command Center
      ↓
6. 🧠 AI Intelligence
      ↓
7. 🔎 Subsurface Communication
      ↓
8. 🧪 Full Integration & Testing
```

---

## 🎯 Goal

> **Build a resilient, decentralized communication and response network that keeps critical information moving when conventional infrastructure fails.**

### **👤 Survivor → 📱 Mesh → 📡 LoRa → 🧠 AI → 🚑 Rescue**
