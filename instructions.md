Smart question. Here is how it works.

The form collects emails into one Kit subscriber list. The list is permanent. 
It grows over time. Every person who enters their email goes into the same list regardless of which guide brought them in.

When someone subscribes today, 
Kit's automation sends them the Chemistry Career Guide PDF. Done.

When you create a new guide in 3 months (say, "LC-MS/MS Method Development Cheat Sheet"), 
you do not need a new form or a new link. You send a broadcast email to your entire existing list:

"I made a new resource: the LC-MS/MS Method Development Cheat Sheet. Here is the download link."

Every subscriber gets it. 
Old subscribers and new ones. 
One click in Kit. This is the core value of an email list: you reach everyone at once, anytime, with anything new.

For the landing page, you have two approaches:

Approach A (simpler, do this now): Keep the current setup. 
The landing page promotes the Chemistry Career Guide as the lead magnet. 
New subscribers get it automatically. 
When you make a second guide, you update the landing page text and the automation email to deliver the new guide instead. 
Or you deliver both guides in the welcome email. One form, updated over time.

Approach B (more flexible, do this later when you have 2-3 guides): 
Change the landing page resource section from one specific guide to a general offer. 
Something like:

"Join 500+ chemists getting free resources on LC-MS/MS, green chemistry, and career strategy. Get instant access to my resource library."

The welcome email then includes links to all your guides:

"Here are your free resources:
1. The Chemistry Career Guide (PDF link)
2. LC-MS/MS Method Development Cheat Sheet (PDF link)
3. Green Metrics Quick Reference (PDF link)"

You update this welcome email in Kit each time you add a new resource. 
The form and the landing page URL stay the same forever.

For today: go with Approach A. You have one guide. Promote it. 
Collect emails. When you have a second resource in a few months, switch to Approach B by updating the welcome email to include both downloads. 
The form URL, the landing page, and the subscriber list never change.

Your nalam.ca page stays the same. Your Kit form stays the same. Only the automated welcome email evolves as your resource library grows.

Now go create the Kit form and paste the action URL into the HTML. You are one step away from a live landing page.

## Brand

Color palette: Warm cream background (#FAF7F2) with terracotta/burnt orange accent (#D4632A), 
sage green and gold secondary colors. No blue anywhere. Editorial, modern, 
Carrd-inspired feel with white cards on cream.

## Kit forms

Two questions, two answers.

---

PHOTO:

Save your professional headshot as a file named `photo.jpg`. When you deploy to Cloudflare Pages, you upload both files together: `index.html` and `photo.jpg` in the same folder.

Then in the HTML, find this line:

```
<div class="avatar">NA</div>
```

Replace it with:

```
<img src="photo.jpg" alt="Dr. Nazmul Alam" style="width:110px;height:110px;border-radius:50%;object-fit:cover;margin:0 auto 24px;display:block;box-shadow:0 0 60px rgba(6,182,212,0.2)">
```

The "NA" initials disappear. Your photo appears.

---

KIT FORM:

Go to kit.com. Log in.

Click "Grow" in the top menu. Then click "Landing Pages & Forms."

Click "Create New." Select "Form" (not Landing Page).

Pick "Inline" form style (not modal or slide-in).

Design does not matter here because you are only using the backend, not Kit's visual form. Your HTML page has its own styled form.

Click "Settings" tab on the form editor. Look for "Form Action URL" or go to the "HTML" embed option. You will see something like:

```
<form action="https://app.kit.com/forms/7654321/subscriptions" method="post">
```

Copy only the URL part: `https://app.kit.com/forms/7654321/subscriptions`

Your number will be different from 7654321.

Now open your index.html file. Find this line:

```
action="https://app.kit.com/forms/YOUR_FORM_ID/subscriptions"
```

Replace it with your actual URL. There is only one place to change it in this version of the page.

Next, set up the automated PDF delivery in Kit:

Still in Kit, click "Automate" in the top menu. Click "Create Automation." Set the trigger to: "When someone subscribes to [your form name]." Add an action: "Send email." Write the email:

Subject: Your Chemistry Career Guide is here
Body: "Here is your free copy of The Chemistry Career Guide. [Download link]"

For the download link, upload your career guide PDF to Google Drive. Set sharing to "Anyone with the link." Copy the link. Paste it into the email body.

Publish the automation. Test it by subscribing with your own email on your landing page.

---

Summary of your deploy checklist:

1. Create Kit form, copy the form action URL
2. Paste the URL into index.html
3. Set up Kit automation to deliver the PDF
4. Save your headshot as photo.jpg
5. Replace the avatar div with the img tag
6. Upload both files (index.html + photo.jpg) to Cloudflare Pages
7. Connect nalam.ca as custom domain
8. Test the full flow: visit nalam.ca, enter email, receive PDF

Go create the Kit form first. Everything else follows from it.
