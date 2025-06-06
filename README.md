# PostgreSQL Related Question And Answer

---

### ১. PostgreSQL কি?

PostgreSQL হলো একটি ওপেন সোর্স, অবজেক্ট-রিলেশনাল ডাটাবেস ম্যানেজমেন্ট সিস্টেম (ORDBMS)। এটি ডাটাবেস তৈরি, পরিচালনা এবং ডেটা সংরক্ষণের জন্য ব্যবহৃত হয়। PostgreSQL উচ্চমানের ডেটা ইন্টিগ্রিটি এবং বিস্তৃত ফিচার সমর্থন করে।

---

### ২. PostgreSQL-এ ডাটাবেস স্কিমার উদ্দেশ্য কি?

ডাটাবেস স্কিমা হলো একটি লজিক্যাল কাঠামো যা ডাটাবেসের টেবিল, ভিউ, ইনডেক্স, এবং অন্যান্য অবজেক্টগুলোকে সংগঠিত করে। এটি ডাটাবেসের অবজেক্টগুলোকে গ্রুপ করে এবং ডাটাবেসের নিরাপত্তা ও ব্যবস্থাপনাকে সহজ করে।

---

### ৩. PostgreSQL-এ প্রাইমারি কি এবং ফরেন কি কি?

- **প্রাইমারি কি (Primary Key):** একটি টেবিলের এমন একটি কলাম বা কলামগুলোর সমষ্টি যা প্রতিটি রেকর্ডকে ইউনিকভাবে চিহ্নিত করে। এটি null হতে পারে না।
- **ফরেন কি (Foreign Key):** একটি টেবিলের কলাম যা অন্য টেবিলের প্রাইমারি কি বা ইউনিক কি রেফার করে, যা টেবিলগুলোর মধ্যে সম্পর্ক স্থাপন করে।

---

### ৪. VARCHAR এবং CHAR ডেটা টাইপের মধ্যে পার্থক্য কি?

- **CHAR:** একটি নির্দিষ্ট দৈর্ঘ্যের স্ট্রিং ডেটা টাইপ, যেখানে ডেটা ছোট হলে বাকি স্পেস ফাঁকা রাখা হয়।
- **VARCHAR:** পরিবর্তনশীল দৈর্ঘ্যের স্ট্রিং ডেটা টাইপ, যেখানে ডেটার দৈর্ঘ্য অনুযায়ী স্পেস ব্যবহৃত হয়।

---

### ৫. SELECT স্টেটমেন্টে WHERE ক্লজের উদ্দেশ্য কি?

WHERE ক্লজ ব্যবহার করে ডাটাবেস থেকে নির্দিষ্ট শর্ত পূরণ করে রেকর্ডগুলো নির্বাচন করা হয়। এটি ডেটা ফিল্টার করার জন্য ব্যবহৃত হয়।
