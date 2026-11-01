---
description: Bu makineyi Agent Office'e bağla
argument-hint: "[--server <url>]"
allowed-tools: Bash(node:*)
---

Agent Office Relay'ini bu makineye bağla. Aşağıdaki komutu Bash tool'uyla çalıştır ve
çıktısının tamamını kullanıcıya göster:

```sh
node "${CLAUDE_PLUGIN_ROOT}/relay/main.js" login $ARGUMENTS
```

Komut bir kullanıcı kodu ve bir cihaz bağlantısı yazar. Kullanıcıya bağlantıyı tarayıcıda
açıp kodu onaylamasını söyle. Komut token'ı alana kadar bekler; Bash komutunu en az 10
dakikalık bir zaman aşımıyla çalıştır. Çıktıda `Giriş yapıldı.` görününce işlem biter.
