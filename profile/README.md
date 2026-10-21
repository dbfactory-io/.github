# dbfactory 🐘

I'm Gilles Fauvie. Fifteen years of PostgreSQL and infrastructure, from Belgium. dbfactory is where I put that work.

**A backup you never restored is a guess.** I have seen a database lost that everybody thought was backed up. Nobody had ever tried a restore. That is the problem I work on.

**pgCellar** is a control room on top of Barman. It shows where your backups are, how far back you can go, and every week it restores the latest one, starts it, looks inside and writes a dated PDF. When the auditor asks "show me it restores", you hand over the PDF. Not a promise.

**Services.** Highly available PostgreSQL clusters (if a node dies, another one takes over), audits with a clear report, and on-call for the databases you can't afford to lose.

**How I work.** I decide, AI agents write a big part of the code under my direction, and everything is tested on real servers before it ships. One person answers when something breaks. Me.

**Links**

- Site: https://dbfactory.io
- pgCellar docs: https://pgcellar.dbfactory.io/docs/
- Demo: https://demo.pgcellar.dbfactory.io (login `demo` / `demo`, read only)
- Blog: https://stranix.net

The tool restores your database every week, so you don't have to find out at 3 a.m.
