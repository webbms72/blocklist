# Random Chat Block List for Pi-hole

A Pi-hole block list for anonymous chat and video roulette sites (e.g. ChatRoulette, Omegle alternatives). Designed for DNS sinkholes to block access to random stranger chat platforms.

## Pi-hole Block List URL

```
https://raw.githubusercontent.com/webbms72/blocklist/main/randomchat-block.txt
```

## How to Add to Pi-hole

1. Open your Pi-hole admin interface
2. Go to **Group Management** → **Adlists** (or **Settings** → **Blocklists** on older versions)
3. Paste the URL above into the address field
4. Click **Add**
5. Go to **Tools** → **Update Gravity** (or run `pihole -g` via SSH)

## List Details

- **Domains:** 346
- **Format:** Plain domain list (one per line), Pi-hole compatible
- **Last updated:** August 2026
- **Scope:** Anonymous/random chat sites, video roulette platforms, Omegle-style alternatives

## License

MIT License - see [LICENSE](LICENSE) for details.
