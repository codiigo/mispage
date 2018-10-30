# MISPage
dev stage for MIS homepage

[Removing large files from Git without losing history](https://support.acquia.com/hc/en-us/articles/360004334093-Removing-large-files-from-Git-without-losing-history)

### Wiping and restarting
If your [packfile](https://git-scm.com/book/en/v2/Git-Internals-Packfiles) is out of control, your best option is to wipe the repository and restart. If your repository doesn't shrink to its expected initial size even after you've performed the maintenance (+ git gc), the packfile may be causing the issue. You can use a command similar to the following one from within the repo:

```bash
find . -type f -name "*.pack" | xargs du -h
```

This is the last resort. If this is necessary, you may find the article to Reset a Git repository on Acquia Cloud useful.

---

### TODO LIST

- [x] Git Repo
- [x] Transparent Navbar
- <strike>[ ] sftp Filezilla</strike> `not working`
- [ ] [Formspree](https://formspree.io) `OR use MailThis.to`
- [ ] [MailThis.to](https://mailthis.to/)
- [ ] Mobile Responsive design
- [ ] [Frontend Checklist](https://frontendchecklist.io)
- [x] Privacy & Cookie Policy
- [ ] SEO (json-ld format)
