# aisolution-mcp

**כלי MCP בעברית לעסקים** | נבנה על ידי [שי קליין](https://aisolution.co.il)

כל הכלים פועלים ב-Claude Desktop וב-Claude Code — התקנה בפקודה אחת.

---

## כלים זמינים

| כלי | תיאור | התקנה |
|-----|-------|--------|
| [hiring-kit-mcp](https://github.com/shayklain/hiring-kit-mcp) | ערכת גיוס מלאה: מכרז, שאלות, בדיקת התאמה | `npx hiring-kit-mcp` |
| *(בקרוב)* proposal-kit-mcp | מחולל הצעות מחיר | — |
| *(בקרוב)* debt-collection-mcp | סדרת הודעות גביית חובות | — |
| *(בקרוב)* sop-generator-mcp | מחולל נהלי עבודה | — |

---

## התקנה מהירה (Claude Code)

```bash
# ערכת גיוס
claude mcp add hiring-kit npx hiring-kit-mcp
```

## התקנה (Claude Desktop)

הוסף ל-`claude_desktop_config.json`:

```json
{
  "mcpServers": {
    "hiring-kit": {
      "command": "npx",
      "args": ["hiring-kit-mcp"]
    }
  }
}
```

---

*[aisolution.co.il](https://aisolution.co.il) · AI לארגונים*
