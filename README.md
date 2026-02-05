# OpenClaw Backup

Backup data OpenClaw dari Codespaces.

## 📁 Struktur Folder
openclaw-data/
├── skills/           # Custom skills
│   └── bankr/       # Skill bankr
├── config/          # Konfigurasi
│   └── openclaw.json
└── README.md
## 🔧 Cara Restore

1. Install OpenClaw: `npm install -g openclaw`
2. Copy skills: `cp -r openclaw-data/skills/* ~/.openclaw/skills/`
3. Copy config: `cp openclaw-data/config/openclaw.json ~/.openclaw/`
4. Restart gateway: `openclaw gateway restart`

## ⚠️ Catatan

- API keys TIDAK disertakan (lihat .gitignore)
- Credentials harus di-setup manual
- Session data tidak di-backup (terlalu besar)

---

**Last backup:** [TANGGAL HARI INI]
