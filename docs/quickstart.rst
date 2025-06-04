{
  "name": "Cheater Tracker",
  "roles": [
    {
      "name": "CT| Founder",
      "permissions": "administrator",
      "color": "#FF0000"
    },
    {
      "name": "CT| Management",
      "permissions": ["manage_channels", "manage_roles", "kick_members", "ban_members", "view_audit_log"],
      "color": "#FF5555"
    }
  ],
  "categories": [
    {
      "name": "📢・INFORMATION",
      "channels": [
        {"name": "📄｜regeln", "type": "text"},
        {"name": "📢｜ankündigungen", "type": "text"},
        {"name": "🆘｜faq", "type": "text"}
      ]
    },
    {
      "name": "💬・COMMUNITY",
      "channels": [
        {"name": "💬｜chat", "type": "text"},
        {"name": "🤖｜bot-commands", "type": "text"},
        {"name": "🎮｜matchmaking", "type": "text"}
      ]
    },
    {
      "name": "👥・SUPPORT",
      "channels": [
        {"name": "📩｜ticket-support", "type": "text"},
        {"name": "🧾｜ticket-log", "type": "text", "private": true, "allowed_roles": ["CT| Management"]}
      ]
    },
    {
      "name": "🔒・TEAM",
      "channels": [
        {"name": "👑｜founder-chat", "type": "text", "private": true, "allowed_roles": ["CT| Founder"]},
        {"name": "⚙️｜management-intern", "type": "text", "private": true, "allowed_roles": ["CT| Management"]},
        {"name": "🗃｜protokolle", "type": "text", "private": true, "allowed_roles": ["CT| Management"]}
      ]
    },
    {
      "name": "📉・LOGS",
      "channels": [
        {"name": "🚨｜mod-log", "type": "text", "private": true, "allowed_roles": ["CT| Management"]},
        {"name": "🛠️｜bot-log", "type": "text", "private": true, "allowed_roles": ["CT| Management"]}
      ]
    }
  ]
}

