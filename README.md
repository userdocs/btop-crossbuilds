# btop++ crossbuilds

Static crossbuilds to use with Linux based platforms

Built on Alpine using https://github.com/userdocs/musl-cross-make

Exampled download using `x86_64`:

```bash
wget -q "https://github.com/userdocs/btop-crossbuilds/releases/latest/download/x86_64-linux-musl.tar.gz" -O ~/btop.tar.gz
tar xf "btop.tar.gz" --strip-components=1 -C ~/
```

The rest are available here: https://github.com/userdocs/btop-crossbuilds/releases/latest