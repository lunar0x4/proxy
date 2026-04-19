# Proxy Repository

A repository containing regularly updated proxy lists, organized into three categories: **Mobile**, **Residential**, and **Datacenter**.  
Each update includes `.tar.gz` archives containing proxies grouped by type.

This project is intended for developers, researchers, and network engineers who want to study how different network types behave, classify IP ranges, or build tooling around proxy identification.

---

## 📦 Proxy Categories

### 📱 Mobile
Mobile proxies originate from mobile carrier networks.  
They typically rotate frequently due to carrier‑grade NAT and may behave differently from fixed‑line connections.

**Characteristics**
- Assigned by mobile carriers  
- High rotation  
- Often share large NAT pools  
- Useful for testing mobile‑specific behaviour  

---

### 🏠 Residential
Residential proxies come from consumer ISPs that provide home broadband connections.  
They tend to resemble typical household traffic patterns.

**Characteristics**
- Assigned to home internet customers  
- Moderate stability  
- Behave like standard consumer traffic  
- Useful for testing consumer‑facing services  

---

### 🏢 Datacenter
Datacenter proxies originate from cloud platforms, hosting providers, and VPS servers.  
These are the most common type found in public proxy lists.

**Characteristics**
- Hosted in cloud or server environments  
- Very common in public lists  
- Often easier for services to classify  
- Useful for infrastructure testing and research  

---

## 📁 File Format
Each category is provided as a `.tar.gz` archive.  
The structure may vary depending on the update, but typically includes plain text lists of proxies.

---

## 🔄 Updates
Updates are published manually and may occur at irregular intervals.

---

## 📜 Disclaimer
This repository is for **educational and research purposes only**.  
Always ensure you have permission to use any proxy and follow all applicable laws and service policies.
