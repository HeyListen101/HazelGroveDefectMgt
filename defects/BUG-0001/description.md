# 🐞 BUG-XXXX — [Short Bug Title]

**Date Logged:** 2025-05-15
**Reported By:** PakYouMu  
**Status:** In Progress  
**Severity:** high-priority  
**Type:** backend; security  
**Labels:** high-priority

---

## 🔎 Summary


Takes too much time to receive request, does not indicate to wait if multiple requests to reset password as well. Instead of saying "wait", it will say email not exists. Overall, it lacks information that the user should be aware upon requesting and to avoid spamming.

---

## ✅ Steps to Reproduce

1. Open app 
2. Navigate to forgot password screen
3. Request Password Reset Link

---

## 📷 Expected Behavior

Should receive password reset request immediately; or at least notify the user that the request is processing

---

## 🧨 Actual Behavior

Took too much to receive request

---

## 🖥️ Environment

- OS: Windows 11
- Browser/App Version: Microsoft Edge 133.0.3065.51,  HG.011.000
- Device: Desktop

---

## 🔗 Related Issues or PRs

- GitHub Issue: [#28](https://github.com/HeyListen101/Visita/issues/28)
- Pull Requests: N/A
