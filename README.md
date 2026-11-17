# Bengali Poem Dataset — JSON

বাংলা কবিতার ডেটাসেটটি UTF-8 JSON ফরম্যাটে সংরক্ষিত। এতে ৬,০৭০টি কবিতা, ১৩৭ জন কবি এবং ২১টি শ্রেণি রয়েছে।

## ফাইল

- `Bengali-Poem-Dataset.json` — সম্পূর্ণ JSON ডেটাসেট
- `LICENSE` — উৎস রিপোজিটরির সঙ্গে দেওয়া GPL-3.0 লাইসেন্স টেক্সট

## JSON গঠন

ফাইলের মূল অবজেক্টে `metadata` এবং `records` রয়েছে। প্রতিটি record-এ সাধারণত এই ক্ষেত্রগুলো আছে:

- `poet` — কবির নাম
- `title` — কবিতার শিরোনাম
- `text` — কবিতার মূল লেখা
- `classification` — কবিতার শ্রেণি
- `source_url` — উৎসের URL
- `collected_at` — উৎসে দেওয়া সংগ্রহের সময়
- `source_files` — উৎস রিপোজিটরির মূল ফাইলের নাম

JSONটি UTF-8-এ লেখা এবং `ensure_ascii=false`-সামঞ্জস্যপূর্ণ Bengali text সরাসরি পড়া যায়।

## উৎস ও অধিকার

ডেটাসেটটি [Bengali-Poem-Dataset](https://github.com/mohammad-sheikh-shahinur-rahman/Bengali-Poem-Dataset) থেকে JSON-এ রূপান্তর করা হয়েছে। উৎস রিপোজিটরিটি ৬,০৭০টি কবিতা ও ১৩৭ জন কবির কথা জানায়।

এই রিপোজিটরির আপলোডার সম্পূর্ণ কবিতাগুলো public করার অনুমতি নিশ্চিত করেছেন। কবিতাগুলোর উৎস URL JSON-এ রাখা হয়েছে। `LICENSE` ফাইলটি upstream repository থেকে অপরিবর্তিতভাবে অন্তর্ভুক্ত করা হয়েছে; এটি আলাদা কবিতা বা তৃতীয়-পক্ষের উপকরণের অধিকার সম্পর্কে অতিরিক্ত দাবি করে না।

গবেষণাপত্র: [A Stylometric Dataset for Bengali Poems, NLPIR 2022](https://shuhanmirza.com/assets/files/papers/nlpir22.pdf)
