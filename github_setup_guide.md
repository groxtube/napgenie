# GitHub Repository Setup Guide for NapGenie

## 🎯 **Overview**

This guide will help you set up GitHub repositories for NapGenie to provide:
- Public issue tracking for bug reports and feature requests
- Web hosting for privacy policy and support pages
- Community engagement and feedback collection
- Development transparency

## 📂 **Recommended Repository Structure**

### **Repository 1: `napgenie-web` (Public)**
**Purpose:** Host website, privacy policy, and support pages
**Contents:**
- `index.html` - Landing page
- `privacy-policy.html` - Privacy policy
- `support.html` - Support center
- `README.md` - Repository information

### **Repository 2: `napgenie-app` (Public)**
**Purpose:** Issue tracking, feature requests, and community engagement
**Contents:**
- `README.md` - App information and links
- `.github/ISSUE_TEMPLATE/` - Issue templates
- `CHANGELOG.md` - Release notes and version history

## 🚀 **Step-by-Step Setup**

### **Step 1: Create Web Repository**

1. **Create Repository:**
   - Go to GitHub.com → New Repository
   - Name: `napgenie-web`
   - Description: "NapGenie official website, privacy policy, and support pages"
   - Public repository
   - Initialize with README

2. **Upload Web Files:**
   - Upload `index.html`, `privacy-policy.html`, `support.html`
   - Commit with message: "Add NapGenie website and support pages"

3. **Enable GitHub Pages:**
   - Settings → Pages
   - Source: Deploy from a branch
   - Branch: main, folder: / (root)
   - Save

4. **Your URLs will be:**
   - `https://yourusername.github.io/napgenie-web/`
   - `https://yourusername.github.io/napgenie-web/privacy-policy.html`
   - `https://yourusername.github.io/napgenie-web/support.html`

### **Step 2: Create App Repository for Issues**

1. **Create Repository:**
   - Name: `napgenie-app`
   - Description: "NapGenie sleep sound app - Bug reports, feature requests, and community feedback"
   - Public repository
   - Initialize with README

2. **Create Issue Templates:**
   Create folder `.github/ISSUE_TEMPLATE/` with these files:

   **bug_report.md:**
   ```markdown
   ---
   name: Bug Report
   about: Report a bug or issue with NapGenie
   title: '[BUG] '
   labels: bug
   assignees: ''
   ---

   **Describe the bug**
   A clear description of what the bug is.

   **To Reproduce**
   Steps to reproduce the behavior:
   1. Go to '...'
   2. Tap on '....'
   3. See error

   **Expected behavior**
   What you expected to happen.

   **Screenshots**
   If applicable, add screenshots.

   **Device Information:**
   - Device: [e.g. Samsung Galaxy S21, iPhone 13]
   - OS: [e.g. Android 13, iOS 16]
   - App Version: [e.g. 1.0.13]

   **Additional context**
   Any other context about the problem.
   ```

   **feature_request.md:**
   ```markdown
   ---
   name: Feature Request
   about: Suggest a new feature for NapGenie
   title: '[FEATURE] '
   labels: enhancement
   assignees: ''
   ---

   **Is your feature request related to a problem?**
   A clear description of what the problem is.

   **Describe the solution you'd like**
   A clear description of what you want to happen.

   **Describe alternatives you've considered**
   Other solutions or features you've considered.

   **Additional context**
   Any other context, mockups, or screenshots about the feature request.
   ```

3. **Create README.md:**
   ```markdown
   # 🌙 NapGenie - Sleep Sound App

   Your Baby's Sleep Wish Granted

   ## 📱 Download NapGenie
   - [Google Play Store](link-to-play-store)
   - [Apple App Store](link-to-app-store)

   ## 🐛 Report Issues
   Found a bug? [Report it here](https://github.com/yourusername/napgenie-app/issues/new?template=bug_report.md)

   ## 💡 Request Features
   Have an idea? [Request a feature](https://github.com/yourusername/napgenie-app/issues/new?template=feature_request.md)

   ## 📞 Support
   - [Support Center](https://yourusername.github.io/napgenie-web/support.html)
   - [Privacy Policy](https://yourusername.github.io/napgenie-web/privacy-policy.html)
   - Email: support@napgenie.com

   ## 🔗 Links
   - [Official Website](https://yourusername.github.io/napgenie-web/)
   - [All Issues](https://github.com/yourusername/napgenie-app/issues)
   - [Release Notes](https://github.com/yourusername/napgenie-app/releases)
   ```

### **Step 3: Configure Repository Settings**

1. **Enable Issues:**
   - Repository Settings → Features
   - Ensure "Issues" is checked

2. **Set Up Labels:**
   - Go to Issues → Labels
   - Create labels: `bug`, `enhancement`, `question`, `documentation`, `priority-high`, `priority-low`

3. **Create Milestones:**
   - Issues → Milestones
   - Create milestones for versions: `v1.1.0`, `v1.2.0`, etc.

## 🔗 **Update Your HTML Files**

Replace the placeholder GitHub URLs in your HTML files with your actual repository URLs:

**In both `support.html` and `index.html`, replace:**
- `https://github.com/napgenie/napgenie-app/issues` 
- `https://github.com/napgenie/napgenie-app/issues/new?template=bug_report.md`
- `https://github.com/napgenie/napgenie-app/issues/new?template=feature_request.md`
- `https://github.com/napgenie/napgenie-app/releases`

**With your actual URLs:**
- `https://github.com/YOURUSERNAME/napgenie-app/issues`
- `https://github.com/YOURUSERNAME/napgenie-app/issues/new?template=bug_report.md`
- `https://github.com/YOURUSERNAME/napgenie-app/issues/new?template=feature_request.md`
- `https://github.com/YOURUSERNAME/napgenie-app/releases`

## 📱 **App Store Integration**

### **For Google Play Console:**
- **Website URL:** `https://yourusername.github.io/napgenie-web/`
- **Privacy Policy URL:** `https://yourusername.github.io/napgenie-web/privacy-policy.html`
- **Support URL:** `https://yourusername.github.io/napgenie-web/support.html`

### **For Apple App Store Connect:**
- **Marketing URL:** `https://yourusername.github.io/napgenie-web/`
- **Privacy Policy URL:** `https://yourusername.github.io/napgenie-web/privacy-policy.html`
- **Support URL:** `https://yourusername.github.io/napgenie-web/support.html`

## 🎯 **Benefits of This Setup**

### **For Users:**
- ✅ Easy bug reporting with structured templates
- ✅ Feature request tracking and voting
- ✅ Transparency in development progress
- ✅ Community discussion and feedback

### **For You (Developer):**
- ✅ Organized issue tracking and management
- ✅ User feedback collection and prioritization
- ✅ Professional appearance for app store submissions
- ✅ Free hosting for support documentation
- ✅ Community building and engagement

### **For App Stores:**
- ✅ Professional support infrastructure
- ✅ Transparent privacy policy and terms
- ✅ Clear contact and support methods
- ✅ Demonstrates active development and support

## 📊 **Managing Issues Effectively**

### **Triage Process:**
1. **New Issues:** Review within 24-48 hours
2. **Label Appropriately:** bug, enhancement, question, etc.
3. **Set Priority:** high, medium, low
4. **Assign to Milestone:** target version for resolution
5. **Respond to User:** Acknowledge and provide timeline

### **Communication Tips:**
- Be responsive and professional
- Thank users for feedback
- Provide clear timelines when possible
- Close issues with explanatory comments
- Use GitHub's linking features to connect related issues

This setup provides a professional, scalable foundation for community engagement and support! 🚀
