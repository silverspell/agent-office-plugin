# Agent Office plugin

Claude Code Agent'larını Agent Office'teki sanal ofise bağlayan plugin.

## Kurulum

Claude Code içinde:

```
/plugin marketplace add silverspell/agent-office-plugin
/plugin install agent-office@agent-office
/agent-office:login
```

Node 24 gerekir. Prompt, kod ve transcript içeriği makineden çıkmaz; yalnızca Activity metadata'sı gönderilir.

## Komutlar

- `/agent-office:login`: tarayıcıda cihaz koduyla giriş
- `/agent-office:status`: bağlantı durumu
- `/agent-office:logout`: çıkış
- `/agent-office:forget`: bir sunucuyu unutma
