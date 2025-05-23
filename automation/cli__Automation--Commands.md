# 🛠️ BuiltByWill — CLI Automation Commands

This document tracks every command, script, and workflow used to automate repo creation, license stamping, authorship, and more.

---

## ✅ Initial Setup

```bash
# Create license starter folders
mkdir -p ~/Desktop/dev__Starters/licenses/{mit,gpl,apache,unlicense,proprietary}

# Inject .bw_hash into each license starter
./inject__BW-Hash.sh


# Generate full repo from template IMPORTANT DAILY USE
./spawn.sh mit haven__os--v1


#COMING SOON

# Interpret input like "create mit project called haven__os--v1"
./devconsole.sh create mit project called haven__os--v1
