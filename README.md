<details>
<summary>Translations:</summary>
- [Português Brasileiro](README-ptbr.md)
</details>

# Rinha de Backend
This project was inspired by a community challenge that took place in August 2023.

[Challenge](https://github.com/zanfranceschi/rinha-de-backend-2023-q3)

## Challenge
The challenge consists of creating an API to undergo a stress test, similar to a 
DDoS attack.

## Limitations
The limitations must be distributed among all services in the Docker Compose setup:

- 1.5 vCPU
- 3 GB RAM

### Minimum Services
- Nginx on port 9999
- Two APIs running simultaneously
- Database

---

## Objective of this project
Since I didn't participate in the challenge, I now have the opportunity to use it as a study case to improve my knowledge of optimizations. Taking advantage of the official stress test available, we will follow these steps:

1. Create a minimal version of the API, as basic and simple as possible.
2. Document the stress test results.
3. Develop new versions, optimizing performance step by step.
4. Record and explain the technical decisions made for each version.

### Note
My goal is not to create the "perfect" version but to demonstrate how to improve an API's performance step by step and how each technical decision affects the results.

## Versions
[Golang](https://github.com/mvinif/2023-q3-golang)
