---
description: Bir sunucunun yerel Agent Office kayıtlarını bırak
argument-hint: "--server <url> [--discard]"
allowed-tools: Bash(node:*)
---

Aşağıdaki komutu Bash tool'uyla çalıştır ve çıktısının tamamını kullanıcıya göster:

```sh
node "${CLAUDE_PLUGIN_ROOT}/relay/main.js" forget $ARGUMENTS
```

`--discard` bekleyen Activity'leri siler. Kullanıcı `--discard` vermediyse önce neyin
silineceğini açıkla ve onay almadan komutu çalıştırma.
