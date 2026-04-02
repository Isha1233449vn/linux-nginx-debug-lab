# Linux nginx Debugging Lab

## 📌 Overview

I installed and configured nginx on a Linux virtual machine and learned how to debug issues when it fails.

---

## 🛠️ What I Did

* Installed nginx
* Started and checked the service
* Simulated an error using a Python server
* Investigated and debugged the issue

---

## ❌ Problem

nginx failed to start because another process was already using port 80.

---

## 🔍 Solution

* Identified the process using port 80
* Stopped the conflicting process
* Restarted nginx successfully

---

## 📚 What I Learned

* How to use `systemctl` to manage services
* How to check logs and diagnose issues
* How port conflicts work in Linux

