# taskmobar
literally like a 3 line script, but it wasn't obvious how to do this at first, so I'm sharing.

very simply outputs the active tasks's description for consumption by xmobar (or similar)

![what it looks like](taskmobar.png)

if there are multiple active tasks, you just get the one with the lowest id number

if there are no active tasks, it will output "No active task"

# usage
copy the script to somewhere in your path like `/usr/local/bin` or `~/.local/bin`

add the following command block to your `xmobarrc`:
`, Run Com "taskmobar" [ ] "task" 30`
