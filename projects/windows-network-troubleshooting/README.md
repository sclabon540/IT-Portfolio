# Windows Network Troubleshooting Lab

## Overview

This project demonstrates a basic Windows network troubleshooting process using Command Prompt.

The goal was to practice identifying whether a computer has a working network configuration, can communicate with an external IP address, and can resolve a domain name.

---

## Objective

Use basic Windows networking commands to determine whether a computer has:

- A valid network configuration
- External network connectivity
- Working DNS name resolution

---

## Environment

**Operating System:** Windows

**Tool Used:** Windows Command Prompt

---

## Tools & Commands

The following commands were used during this lab:

```text
ipconfig
ping 8.8.8.8
ping google.com
```

---

# Troubleshooting Process

## Step 1 — Check IP Configuration

I began by checking the computer's network configuration.

### Command Used

```text
ipconfig
```

### What I Checked

I looked for:

- IPv4 address
- IPv6 address
- Subnet mask
- Default gateway

### Result

Network configuration information was present, including IPv4, IPv6, subnet mask, and default gateway information.

### Screenshot

![IP Configuration](ipconfig-results.png)

---

# Step 2 — Test External IP Connectivity

Next, I tested whether the computer could communicate with an external IP address.

### Command Used

```text
ping 8.8.8.8
```

### What I Was Testing

This test checks whether the computer can reach an external IP address.

### Result

The test returned successful replies from the destination.

This confirmed that the computer was able to communicate with the external IP address.

### Screenshot

![Ping 8.8.8.8](ping-ip-results.png)

---

# Step 3 — Test DNS Name Resolution

Next, I tested whether the computer could resolve a domain name.

### Command Used

```text
ping google.com
```

### What I Was Testing

Unlike the previous test, this test uses a domain name instead of an IP address.

This helps determine whether the computer can resolve a hostname and communicate with the destination.

### Result

The test returned successful replies.

This confirmed that the computer was able to resolve the domain name and communicate with the destination.

### Screenshot

![Ping Google](ping-dns-results.png)

---

# Results

| Test | Command | Result |
|---|---|---|
| IP Configuration | `ipconfig` | Network configuration information present |
| External Connectivity | `ping 8.8.8.8` | Successful replies |
| DNS Resolution | `ping google.com` | Successful replies |

---

# Troubleshooting Analysis

The tests were successful.

The computer had network configuration information, successfully communicated with an external IP address, and successfully resolved and communicated with a domain name.

Based on these tests, there was no obvious connectivity or DNS resolution problem during the lab.

---

# What I Learned

This lab helped me understand how basic Windows networking commands can be used as part of a troubleshooting process.

I learned that troubleshooting should be performed systematically instead of immediately assuming what the problem is.

The process I practiced was:

1. Check the computer's network configuration.
2. Test connectivity to an external IP address.
3. Test connectivity using a domain name.
4. Compare the results.
5. Use the results to narrow down the possible cause of a problem.
6. Document the troubleshooting process.

---

# Skills Demonstrated

- Windows troubleshooting
- Basic networking
- IP configuration
- IPv4 fundamentals
- IPv6 fundamentals
- Subnet mask fundamentals
- Default gateway fundamentals
- Network connectivity testing
- DNS troubleshooting fundamentals
- Command Prompt
- Technical documentation
- Problem-solving

---

# Commands Practiced

### `ipconfig`

Used to view network configuration information for the computer.

### `ping`

Used to test network connectivity between the computer and another destination.

### `ping 8.8.8.8`

Used to test connectivity to an external IP address.

### `ping google.com`

Used to test connectivity using a domain name and verify that the hostname could be resolved.

---

# Conclusion

This project gave me hands-on practice with basic Windows network troubleshooting.

By checking network configuration, testing external IP connectivity, and testing DNS name resolution, I practiced a structured approach to diagnosing connectivity problems.

This is one of the foundational troubleshooting processes I can use as I continue developing my skills for an IT support career.

---

# Screenshots

## IP Configuration

![IP Configuration](https://github.com/sclabon540/IT-Portfolio/blob/main/projects/windows-network-troubleshooting/ipconfig-results.png)

## External IP Connectivity

![Ping 8.8.8.8](https://github.com/sclabon540/IT-Portfolio/blob/main/projects/windows-network-troubleshooting/ping-ip-results.png)

## DNS Name Resolution

![Ping Google](https://github.com/sclabon540/IT-Portfolio/blob/main/projects/windows-network-troubleshooting/ping-dns-results.png)

---

## Project Status

**Completed — Beginner IT Support Lab**
