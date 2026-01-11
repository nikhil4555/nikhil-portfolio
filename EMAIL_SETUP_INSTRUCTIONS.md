# EmailJS Setup Instructions

Your contact form is now configured to send real emails using EmailJS. Follow these steps to complete the setup:

## Step 1: Create EmailJS Account
1. Go to [https://www.emailjs.com/](https://www.emailjs.com/)
2. Click "Sign Up" 
3. Sign up with your email: **nikhilgummadavelly05@gmail.com**
4. Verify your email address

## Step 2: Add Email Service
1. In your EmailJS dashboard, go to "Email Services"
2. Click "Add New Service"
3. Choose your email provider (Gmail recommended)
4. Follow the setup instructions to connect your Gmail account
5. Copy your **Service ID** (looks like: `service_abc123`)

## Step 3: Create Email Template
1. Go to "Email Templates" in your dashboard
2. Click "Create New Template"
3. Use this template structure:

**Template Name:** Portfolio Contact Form

**Template Content:**
```
Subject: New Contact Form Message from {{name}}

From: {{name}}
Email: {{email}}
Subject: {{subject}}

Message:
{{message}}

---
This message was sent from your portfolio contact form.
```

4. Save and copy your **Template ID** (looks like: `template_xyz789`)

## Step 4: Get Your Public Key
1. Go to "Account" > "General" in your dashboard
2. Find your **Public Key** (looks like: `user_abcdefghijk123456`)

## Step 5: Update Your Code
Open `script.js` and find these lines (around line 350):

```javascript
// Initialize EmailJS - Replace with your actual public key
emailjs.init("YOUR_PUBLIC_KEY");
```

```javascript
emailjs.sendForm('YOUR_SERVICE_ID', 'YOUR_TEMPLATE_ID', form)
```

Replace the placeholders with your actual values:

```javascript
// Initialize EmailJS
emailjs.init("user_abcdefghijk123456");
```

```javascript
emailjs.sendForm('service_abc123', 'template_xyz789', form)
```

## Step 6: Test Your Form
1. Open your website
2. Fill out the contact form with test data
3. Submit it
4. You should see "Message Sent!" confirmation
5. Check your email inbox for the message

## EmailJS Benefits
- ✅ 200 free emails per month
- ✅ Real-time success/error feedback
- ✅ Custom email templates
- ✅ No server required
- ✅ Direct frontend integration
- ✅ Professional email formatting

## Template Variables
Your form uses these variables that EmailJS will replace:
- `{{name}}` - Sender's name
- `{{email}}` - Sender's email
- `{{subject}}` - Message subject
- `{{message}}` - Message content

## Troubleshooting
- Make sure all three IDs are correct (Public Key, Service ID, Template ID)
- Check browser console for any error messages
- Verify your email service is properly connected
- Test with a simple message first

---

Much more powerful than Formspree! You get custom templates, better error handling, and professional email formatting.