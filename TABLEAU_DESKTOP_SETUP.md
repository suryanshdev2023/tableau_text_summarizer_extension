# 📊 Tableau Desktop Setup Guide

## 🚨 Important for Tableau Desktop Users

**Extensions in Tableau Desktop work differently!**

## ✅ **Required Steps:**

### 1. **Create Worksheets First**
- Create your worksheets with text data (job descriptions, etc.)
- Make sure worksheets have data and are saved

### 2. **Add Worksheets to Dashboard**
- Create a new Dashboard
- **Drag your worksheets** from the left panel onto the dashboard
- You can make them small or hide them if needed

### 3. **Then Add Extension**
- Drag "Extension" object onto dashboard
- Select `text_summarizer.trex`
- Now you should see your worksheets in the dropdown!

## 🔧 **If Still No Worksheets Showing:**

### Check These:
1. **Are worksheets ON the dashboard?** (not just in the workbook)
2. **Do worksheets contain data?**
3. **Are you in a Dashboard view?** (not Worksheet view)
4. **Try refreshing the extension**

### Debug Steps:
1. Press **F12** to open browser console
2. Look for log messages showing worksheet names
3. Should see: "Found X worksheet(s) in dashboard"

## 🎯 **The Key Rule:**
**Tableau Desktop extensions can ONLY see worksheets that are placed ON the current dashboard**

## ✅ **Working Setup:**
```
Dashboard Layout:
├── Worksheet 1 (with your text data)
├── Worksheet 2 (optional)  
└── Extension Object (Text Summarizer)
```

Then the extension will see and list your worksheets! 🚀 