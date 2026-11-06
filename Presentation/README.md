
# Presentation on Routing Information Protocol (RIP)

---

## Student Information

| Field | Details |
|---|---|
| **Name** | MD. Afif Zaman |
| **Student ID** | IT23059 |
| **Department** | Information and Communication Technology (ICT) |
| **University** | Mawlana Bhashani Science and Technology University |
| **Course** | Data Communication |
| **Course Code** | ICT-3101 |
| **Course Teacher** | Dr. Nazrul Islam |
| **Presentation Topic** | Routing Information Protocol (RIP) |

---

## Project Overview

This repository contains my academic presentation on **Routing Information Protocol (RIP)**, prepared for the Data Communication course (ICT-3101).

RIP is one of the earliest dynamic routing protocols used in computer networks. It allows routers to exchange routing information and determine paths to destination networks based on hop count.

The presentation explains how RIP works, its routing mechanisms, different versions, advantages, limitations, and comparisons with other routing protocols.

---

## Presentation Objectives

The main objectives of this presentation are:

- Understand the fundamentals of dynamic routing.
- Explain the working principles of RIP.
- Understand hop count and routing tables.
- Explore routing updates and network convergence.
- Learn how RIP reduces routing loops.
- Compare RIPv1, RIPv2, and RIPng.
- Evaluate the advantages and limitations of RIP.
- Compare RIP with OSPF and EIGRP.

---

## Topics Covered

The presentation consists of **17 slides**, covering the following topics:

1. Introduction
2. Presentation Roadmap
3. The Routing Problem
4. What Is RIP?
5. RIP Topology: Finding the Shortest Path
6. How RIP Learns a Route
7. A Simple Routing-Table Example
8. RIP Essentials
9. When a Link Fails: Convergence
10. How RIP Reduces Routing Loops
11. RIP Versions
12. Advantages and Limitations
13. RIP vs OSPF vs EIGRP
14. Where RIP Makes Sense
15. Key Takeaways
16. Selected References
17. Thank You

---

## Key Concepts

### 1. Distance-Vector Routing

RIP is a distance-vector routing protocol based on the Bellman-Ford principle.

Routers exchange routing information with their neighbors to learn paths to destination networks.

### 2. Hop Count

RIP uses hop count as its routing metric.

- Maximum usable hop count: **15**
- Unreachable destination: **16 hops**
- Normal routing update interval: **30 seconds**
- RIPv1 and RIPv2 UDP port: **520**

### 3. Routing Tables

RIP maintains routing tables containing information about:

- Destination networks
- Next-hop routers
- Hop counts

These tables help routers determine where to forward packets.

### 4. Network Convergence

Convergence is the process through which routers update their routing information after network changes.

RIP may experience relatively slow convergence compared with more advanced routing protocols.

### 5. Routing Loop Prevention

RIP uses several mechanisms to reduce routing loops:

- **Split Horizon:** Prevents advertising a learned route back through the interface where it was learned.
- **Route Poisoning:** Advertises an unreachable destination with a metric of 16.
- **Triggered Updates:** Sends routing updates when important network changes occur.

---

## RIP Versions

| Feature | RIPv1 | RIPv2 | RIPng |
|---|---|---|---|
| IP Version | IPv4 | IPv4 | IPv6 |
| Routing Type | Classful | Classless | IPv6 Prefix-Based |
| Subnet Information | Not Advertised | Supported | Supported |
| Update Method | Broadcast | Multicast | Multicast |
| UDP Port | 520 | 520 | 521 |

---

## RIP vs Other Routing Protocols

| Feature | RIP | OSPF | EIGRP |
|---|---|---|---|
| Routing Approach | Distance Vector | Link State | Advanced Distance Vector |
| Primary Metric | Hop Count | Cost | Composite Metric |
| Convergence | Relatively Slow | Generally Fast | Generally Fast |
| Scalability | Limited | High | High |
| Configuration | Simple | More Complex | Moderate |

---

## Advantages of RIP

- Simple configuration and implementation.
- Easy to understand and learn.
- Suitable for small networks.
- Useful for networking education and laboratory exercises.
- Automatically exchanges routing information.

---

## Limitations of RIP

- Maximum of 15 usable hops.
- Relatively slow convergence.
- Does not consider bandwidth or delay when selecting routes.
- Limited scalability in large networks.
- Less suitable for complex modern networks.

---

## Presentation Files

| File | Description |
|---|---|
| `RIP_Presentation.pptx` | PowerPoint presentation |
| `RIP_Presentation.pdf` | PDF version of the presentation |
| `README.md` | Repository documentation |

---

## Presentation Video

The presentation recording will be available here.

**Watch the Presentation:** [Click Here](https://drive.google.com/file/d/1NEvM4-9NTiFLxlTwY_1pCa14tnqG4m0c/view?usp=drivesdk)

---

## References

1. **RFC 1058 - Routing Information Protocol**  
   https://www.rfc-editor.org/rfc/rfc1058

2. **RFC 2453 - RIP Version 2**  
   https://www.rfc-editor.org/rfc/rfc2453

3. **RFC 2080 - RIPng for IPv6**  
   https://www.rfc-editor.org/rfc/rfc2080

4. **RFC 4822 - RIPv2 Cryptographic Authentication**  
   https://www.rfc-editor.org/rfc/rfc4822

---

## Conclusion

Routing Information Protocol is an important foundation for understanding dynamic routing in computer networks.

Although RIP has limitations in scalability and convergence speed, its simple operation makes it valuable for learning routing concepts and understanding how routers exchange network information.

---

## Prepared By

**MD. Afif Zaman**  
**Student ID:** IT23059  
**Department:** Information and Communication Technology  
**University:** Mawlana Bhashani Science and Technology University  
**Course:** Data Communication (ICT-3101)  
**Course Teacher:** Dr. Nazrul Islam

