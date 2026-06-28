# Namecheap DNS to GitHub Pages Guide

Go to Namecheap → Domain List → queenayodele.com → Manage → Advanced DNS.

Add these records:

A Record | Host: @ | Value: 185.199.108.153 | TTL: Automatic
A Record | Host: @ | Value: 185.199.109.153 | TTL: Automatic
A Record | Host: @ | Value: 185.199.110.153 | TTL: Automatic
A Record | Host: @ | Value: 185.199.111.153 | TTL: Automatic

CNAME Record | Host: www | Value: YOURGITHUBUSERNAME.github.io | TTL: Automatic

Replace YOURGITHUBUSERNAME with your GitHub username.

DNS can take 10 minutes to 24 hours.
