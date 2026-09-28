# roblox-scripts

รวม script Roblox ทั้งหมดไว้ที่เดียว แยกโฟลเดอร์ตามเกม

| เกม | ไฟล์ | Repo เดิม |
|---|---|---|
| Be a YouTuber | [`be-a-youtuber/be-a-youtuber.lua`](be-a-youtuber/be-a-youtuber.lua) | `xRaphaelz/script` |
| Anime Ghost | [`anime-ghost/anime-ghost.lua`](anime-ghost/anime-ghost.lua) | `xRaphaelz/anime-ghost-script` |
| Survive Zombie Arena | [`survive-zombie-arena/survive-zombie-arena.lua`](survive-zombie-arena/survive-zombie-arena.lua) | `xRaphaelz/Survive-Zombie-Arena-script` |
| Murder Mystery 2 | [`mm2/mm2.lua`](mm2/mm2.lua) | `xRaphaelz/MM2-script` |
| +1 Mine Per Click | [`plus-1-mine-per-click/plus-1-mine-per-click.lua`](plus-1-mine-per-click/plus-1-mine-per-click.lua) | `xRaphaelz/-1-Mine-Per-Click-script` |

## เพิ่ม / อัปเดต script

- **อัปเดต:** เขียนทับไฟล์เดิมในโฟลเดอร์ของเกมนั้น ใช้ชื่อไฟล์เดิม ไม่ต้องใส่ timestamp เพราะ git เก็บประวัติให้แล้ว
- **เกมใหม่:** สร้างโฟลเดอร์ `<ชื่อเกม>/` ใส่ไฟล์ `<ชื่อเกม>.lua` แล้วเพิ่มแถวในตารางด้านบน

```bash
git add .
git commit -m "mm2: <สิ่งที่เปลี่ยน>"
git push
```
