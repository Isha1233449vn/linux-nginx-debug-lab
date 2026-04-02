# Linux nginx Debugging Lab

## Overview

I installed nginx on a Linux virtual machine and learned how to debug issues when it fails.

## What I Did

* Installed nginx
* Started the service
* Simulated an error using a Python server
* Debugged the issue

## Problem

nginx failed to start because another process was using port 80.

## Solution

I found the process using port 80 and stopped it, then restarted nginx.

## What I Learned

* How to use systemctl
* How to check logs
* How port conflicts work
