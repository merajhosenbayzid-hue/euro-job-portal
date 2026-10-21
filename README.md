# Euro Job Portal

ইউরোপের সব দেশের যাচাই করা জব পোর্টাল এক জায়গায় — প্রতিটি দেশের সবচেয়ে বড় পোর্টাল ও সরকারি কর্মসংস্থান ওয়েবসাইট। শুধু ইউরোপের দেশ (বাইরের কোনো দেশ নেই)।

Live: https://merajhosenbayzid-hue.github.io/euro-job-portal/

## পরে কাস্টম ডোমেইন যোগ করা (ট্রাফিক নষ্ট না করে)
1. ডোমেইন কিনুন (যেমন eurojobportal.com)।
2. এই GitHub repo → Settings → Pages → Custom domain-এ ডোমেইনটা বসান — GitHub নিজে থেকেই পুরনো github.io লিংক থেকে নতুন ডোমেইনে **অটো-রিডাইরেক্ট** দেবে, তাই পুরনো লিংক/ট্রাফিক হারাবে না।
3. ডোমেইন প্রোভাইডারে DNS: `www`-এর জন্য CNAME → `merajhosenbayzid-hue.github.io`, root-এর জন্য GitHub Pages-এর A রেকর্ড।
4. তারপর একটিমাত্র কমিটে `index.html`-এর canonical/OG URL, `sitemap.xml` ও `robots.txt`-এর ঠিকানা নতুন ডোমেইনে বদলাতে হবে (সহকারীকে বললেই করে দেবে)।
5. Google Search Console-এ নতুন ডোমেইনের প্রপার্টি যোগ + পুরনো প্রপার্টিতে Change of Address — এতে গুগলের র‍্যাংক/ট্রাফিক নতুন ডোমেইনে চলে যাবে।
