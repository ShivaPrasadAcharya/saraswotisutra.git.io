# Help - Quick Reference Guide

Welcome to Bharati Sutra! This guide provides quick answers to common questions and tasks.

---

## 📚 Quick Start

### Getting Started in 30 Seconds
1. **Open the app** → Click a note in the left sidebar
2. **View content** → Read the rendered markdown
3. **Search text** → Click search box (top-right), type your query
4. **Switch theme** → Click sun/moon icon in top toolbar

### First-Time Tips
- Notes appear in the **left sidebar** under "📖 Notes"
- Click **Master TOC** to see all available notes
- Use **breadcrumb navigation** (top) to track your location
- **Search** works across all visible content

---

## 🎯 Main Features

### 1. Viewing & Searching
| Action | How |
|--------|-----|
| **Read a note** | Click note name in sidebar |
| **Search text** | Click search box, type query, use ↑↓ arrows |
| **Find & highlight** | Use search with real-time highlighting |
| **View TOC** | Click "Master TOC" in sidebar |

### 2. Filtering & Sorting Tables
| Action | How |
|--------|-----|
| **Filter table rows** | Click "Show/Hide" → Add rules → Apply |
| **Sort table** | Click "Show/Hide" → Select column → Choose method → Apply |
| **Reset table** | Click 🔄 Refresh button |
| **Show fewer rows** | Use "Show" dropdown (5, 10, 25, 50, 100, All) |

### 3. Exporting Data
| Action | How |
|--------|-----|
| **Copy table** | Click 📋 Copy → Select format (Markdown/JSON/CSV/HTML/TSV) |
| **Download PDF** | Click 📥 PDF button |
| **Print note** | Press Ctrl+P (Cmd+P on Mac) |

### 4. Theme & Display
| Action | How |
|--------|-----|
| **Change theme** | Click 🌙/☀️ icon (top-right) |
| **Adjust text size** | Use browser zoom (Ctrl/Cmd + ±) |
| **Full screen** | Press F11 in browser |

---

## ❓ Frequently Asked Questions

### How do I add my own notes?
Edit the `datanoteU14.js` file and add your content to the note structure. See README.md for detailed configuration.

### Why can't I sort/filter?
Make sure you clicked **"Show/Hide"** button first to reveal the filter panel. Some tables may be locked.

### How do I search in multiple notes?
The search works on the **currently displayed note**. To search across notes, you need to read through them individually or use your browser's find function (Ctrl+F).

### Can I password-protect my notes?
Yes! Add `meta: { password: "yourPassword" }` to a note configuration. See README.md for details.

### How do I export filtered results?
1. Apply your filters
2. Click 📋 Copy
3. Select format
4. Only filtered rows are exported

### Does this work offline?
Yes! Open `index.html` locally in your browser. No internet needed.

### Can I print tables cleanly?
Yes! Press Ctrl+P to print. Filters and search bars automatically hide. Use "Save as PDF" for digital copies.

### How do I reset a table to original state?
Click the 🔄 **Refresh** button. It undoes all sorting, filtering, and column changes instantly.

---

## ⚡ Common Tasks

### Task: Find all Active Users
```
1. Navigate to Users table
2. Click "Show/Hide"
3. Column: Status | Operator: equals | Value: Active
4. Click "Apply"
5. Result: Only active users shown
```

### Task: Sort by Highest Sales
```
1. Navigate to Sales table
2. Click "Show/Hide"
3. Sort by: Sales column | Method: Descending
4. Click "Apply Sort"
5. Result: Highest sales first
```

### Task: Export 25 employees to Excel
```
1. Go to Employee table
2. Set "Show" to 25 entries
3. Click 📋 Copy → Select "CSV"
4. Paste into Excel
5. Done!
```

### Task: Find text in a note
```
1. Click search box (top-right)
2. Type your search term
3. Use ↑↓ arrows to navigate matches
4. Click X to close search
```

### Task: Compare filtered results in Excel
```
1. Apply filters to table
2. Click 📋 Copy → JSON
3. Use online JSON-to-CSV converter
4. Paste into Excel
5. Analyze data
```

---

## 🔧 Troubleshooting

### Problem: Search not working
**Solution:** Make sure you typed in the search box and it has focus (cursor visible).

### Problem: Filter shows no results
**Solution:** 
- Check if filter rules are too restrictive
- Try clearing filters and applying simpler rules
- Verify the search value matches actual data

### Problem: Sort doesn't work
**Solution:**
- Make sure you selected a column
- Click "Apply Sort" button
- Check console for errors (F12)

### Problem: Can't copy table
**Solution:**
- Some tables may be protected
- Try a different format
- Check browser console (F12) for errors

### Problem: PDF download doesn't start
**Solution:**
- Check browser's download settings
- Allow pop-ups for this site
- Try a different browser

### Problem: Theme not saving
**Solution:**
- Check if browser allows local storage
- Disable privacy mode/incognito
- Clear browser cache and try again

### Problem: Mobile view looks broken
**Solution:**
- Try rotating device
- Increase browser zoom slightly
- Disable browser zoom and try again

---

## 🎨 Keyboard Shortcuts

| Shortcut | Action |
|----------|--------|
| `/` | Focus search box |
| `Escape` | Clear search / Close modals |
| `Ctrl+P` / `Cmd+P` | Print page |
| `Ctrl+Shift+D` | Toggle theme |
| `Ctrl+F` | Browser find (searches current page) |

---

## 📞 Need More Help?

- **Full Documentation**: See **README.md** for detailed guides
- **Table Features**: Check README → Usage Guide → Advanced Filtering/Sorting
- **Export Formats**: Check README → Table Export Formats
- **Configuration**: Check README → Configuration section

---

## 💡 Pro Tips

✅ **Use Custom Functions** for advanced sorting (extract numbers, dates, etc.)

✅ **Combine Filters** with AND/OR logic for complex queries

✅ **Export Early** - Copy filtered/sorted data to external tools for analysis

✅ **Use PDF Export** to share notes with others professionally

✅ **Master TOC** saves time - see all notes at a glance

✅ **Refresh Button** beats page reload - instant reset without losing position

---

## 🚀 Performance Tips

- **Large tables?** Use "Show" dropdown to display fewer rows at once
- **Lots of notes?** Use search to quickly find specific content
- **Multiple filters?** Start simple, then add complexity
- **Export often** - Store important data externally as backup

---

Last updated: January 2026
