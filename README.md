# Birthday Weekend Website 🎉

A beautiful, multi-page website for your birthday weekend in Phoenix, AZ (Feb 27 – Mar 2, 2026).

## 📁 Files Included

- `index.html` - Homepage with overview and quick info
- `guests.html` - Meet the Squad page with photos and social media
- `message.html` - Message from the Birthday Girl
- `events.html` - Full itinerary with daily events and dress codes
- `styles.css` - Shared styles for all pages
- `events-styles.css` - Additional styles for the events page
- `script.js` - Navigation and interactive features
- `photos/` - Folder for all your photos

## 📸 Adding Photos to Your Site

### Photos You Need:

1. **birthday-girl.jpg** - Your photo (used on both The Squad page and Message page)
2. **friend1.jpg** - Friend arriving Friday afternoon
3. **friend2.jpg** - Friend arriving Friday afternoon  
4. **friend3.jpg** - Friend arriving Friday ~10pm
5. **friend4.jpg** - Friend arriving Saturday ~11am
6. **arizona.jpg** - A beautiful Arizona desert/landscape photo for the homepage

### How to Add Photos:

**Before Uploading to GitHub:**
1. Rename your photos to match the names above exactly (birthday-girl.jpg, friend1.jpg, etc.)
2. Put all photos in the `photos` folder
3. Make sure they're JPG format
4. Recommended size: 500-1000px wide for best quality

**Recommended Photo Specs:**
- **Guest photos**: Square photos work best (they'll be cropped to circles)
- **Arizona photo**: Landscape orientation, 1200-1600px wide
- **File size**: Keep under 1MB each for fast loading

### Finding an Arizona Photo:
You can use a free photo from [Unsplash](https://unsplash.com/s/photos/arizona-desert) or [Pexels](https://www.pexels.com/search/arizona/) - just download and rename it to `arizona.jpg`

## 📌 Adding Your Pinterest Boards

### Where to Add Pinterest Links:

In the `events.html` file, find these three sections and replace `https://www.pinterest.com/your-board-link` with your actual Pinterest board URLs:

1. **Friday Theme** - "Blooming Into 27" (Line ~52)
2. **Saturday Theme** - "Cowgirl Couture" (Line ~142)  
3. **Sunday Theme** - "Boots With The Fur" (Line ~310)

### How to Get Pinterest Board Links:
1. Create a Pinterest board for each theme
2. Click "Share" on the board
3. Copy the board link
4. Paste it in place of `https://www.pinterest.com/your-board-link`

## 👥 Updating Guest Info

### In `guests.html`, update for each person:

```html
<h3 class="guest-name">Friend #1 Name</h3>  <!-- Replace with real name -->
<p class="guest-role">Arriving Friday Afternoon</p>  <!-- Keep or customize -->
<div class="guest-socials">
  <a href="https://instagram.com/username">📸 @username</a>  <!-- Instagram handle -->
  <a href="sms:+1234567890">📱 Contact</a>  <!-- Phone number -->
</div>
```

### Social Media Options:
- **Instagram**: `https://instagram.com/username`
- **Phone**: `sms:+1234567890` (use actual phone number)
- **Email**: `mailto:email@example.com`
- **Twitter/X**: `https://twitter.com/username`

You can add more links or remove the ones you don't need!

## 🚀 Deploy to GitHub Pages (100% Free!)

### Step 1: Create a GitHub Account
If you don't have one already, sign up at [github.com](https://github.com)

### Step 2: Create a New Repository
1. Click the **+** button in top right → **New repository**
2. Name it whatever you want (e.g., `birthday-weekend`)
3. Make it **Public**
4. Don't add README, .gitignore, or license
5. Click **Create repository**

### Step 3: Upload Your Files
1. On the repository page, click **Add file** → **Upload files**
2. Drag and drop ALL the files from the `birthday-site` folder:
   - index.html
   - guests.html
   - message.html
   - events.html
   - styles.css
   - events-styles.css
   - script.js
3. Click **Commit changes**

### Step 4: Enable GitHub Pages
1. Go to **Settings** tab (top right of your repo)
2. Scroll down to **Pages** (left sidebar)
3. Under **Source**, select **main** branch
4. Click **Save**
5. Wait 1-2 minutes, then refresh the page
6. You'll see: "Your site is published at `https://yourusername.github.io/birthday-weekend`"

### Step 5: Share the Link!
Copy the URL and send it to all your friends. They can:
- Bookmark it on their phones
- View it on any device
- Check the full itinerary anytime

## 📱 Features

✅ **Fully responsive** - looks great on phones, tablets, and desktops
✅ **Smooth navigation** - jump between pages easily
✅ **Mobile menu** - hamburger menu on small screens
✅ **Day-by-day itinerary** - with themes and dress codes
✅ **Quick links** - to booking sites and important info
✅ **Beautiful design** - custom fonts and animations

## 🎨 Customization

### To Edit Content:
Just open any `.html` file in a text editor and change the text between the `<div>` tags.

### To Update Guest Names:
Edit `guests.html` - find the guest cards and update:
- `<h3 class="guest-name">Your Name</h3>`
- `<p class="guest-role">Your Role</p>`
- `<p class="guest-bio">Your Bio</p>`

### To Change Colors:
Edit `styles.css` - the colors are defined at the top:
```css
:root {
  --rose: #e8917a;
  --gold: #c9a96e;
  --blush: #e4b4c2;
  --lilac: #c4aad6;
}
```

## 🔄 Updating After Deployment

Whenever you make changes:
1. Go to your GitHub repository
2. Click on the file you want to edit
3. Click the pencil icon (Edit)
4. Make your changes
5. Click **Commit changes**
6. Wait ~1 minute for changes to go live

## 💡 Tips

- **No domain needed** - your free GitHub Pages URL works perfectly
- **Share via text** - just send friends the link
- **Screenshot friendly** - all pages look great in screenshots
- **Print option** - friends can print the itinerary if needed

## 📞 Support

If you need help:
1. Check that all files are uploaded
2. Make sure you selected the **main** branch in Settings → Pages
3. Wait a few minutes after enabling Pages
4. Try the URL in an incognito window

---

**Your site will be live at:**
`https://YOUR-GITHUB-USERNAME.github.io/REPO-NAME`

Example: `https://janedoe.github.io/birthday-weekend`

🎉 **That's it! Your birthday weekend website is ready to share!**
