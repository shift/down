# The Deeper Problem

> 📍 Late Game · 7 decisions made

You fix the disk. Kill the query. Optimize the indexes. Professional, boring, effective.

But at 4am you notice something worse. The backup script has a typo — `bckup` instead of `backup`. It's been silently failing since January. Last successful backup: 8 months ago.

You are the only person who knows this.

*This is literally what happened to GitLab on January 31, 2017. An engineer ran a deletion command on the wrong database. 6 hours of production data gone. The backups? Five different backup mechanisms. None of them worked. The post-mortem reads like a comedy of errors. It was not funny at the time.*

---

- [Fix the script, run a full backup now](../trusted)
- [Report it to your manager immediately](../trusted)
- [Fix it but don't tell anyone](./secret)
