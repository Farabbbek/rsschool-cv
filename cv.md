# Tusup Al-Farabi

## Contacts
- Email: ftusup@bk.ru
- Telegram: @FarabvsArab

## About Me
I am student in Astana IT University.
Faculty Cybersecurity.
I am just learn all about information technology.

## Skills
- JS
- HTML&CSS
- Git
- Golang
- Sql

## Code Example
```
package main

import "strings"

func IsValidSlug(s string) bool {
 if s == "" {
  return false
 }
 if len(s) < 1 || len(s) > 64 {
  return false
 }
 if s[0] == '-' || s[len(s)-1] == '-' {
  return false
 }
 if strings.Contains(s, "--") {
  return false
 }
 for _, d := range s {
  if !(d == '-' || (d >= '0' && d <= '9') || (d >= 'a' && d <= 'z')) {
   return false
  }
 }
 return true
}
```
## Languages
  + English(B1)
  + Russian(C2)
  + Kazakh(C2)
## Certificate
  + Cisco Network Fundamentals
  + Linux Essentials
  + Python Engineering
## Project
- Web app Fitness Tracker (Django,SQL,Python)
- Cybersecurity Project
