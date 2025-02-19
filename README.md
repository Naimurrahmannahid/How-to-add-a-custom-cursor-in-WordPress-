# How to add a custom cursor in WordPress?

Enhance your website's user experience with Kursor.js, a lightweight JavaScript library for adding custom cursors. Easily customize cursor styles, colors, and effects for a unique interactive feel.

## সঠিক কোড:

<link rel="stylesheet" href="https://unpkg.com/kursor/dist/kursor.css">
<script src="https://unpkg.com/kursor/dist/kursor.min.js"></script>
<script>
  new kursor({
    type: 1,
    color: '#000000',
    removeDefaultCursor: false,
  });
</script>

## সমস্যা এবং সমাধান:

আপনার দেওয়া JavaScript ফাইলের লিংক ভুল ছিল (/dist/kursor.js), যা পরিবর্তন করে /dist/kursor.min.js করতে হবে।
লাইব্রেরি লোড না হলে কাজ করবে না:

Kursor.js সঠিকভাবে লোড না হলে কোড কাজ করবে না।
কনসোল (F12 > Console) এ error দেখলে নিশ্চিত করুন যে লাইব্রেরিটি লোড হচ্ছে কিনা।
ডিফল্ট কার্সর রিমুভ করতে চাইলে:

new kursor({
  type: 1,
  color: '#000000',
  removeDefaultCursor: true, // ডিফল্ট কার্সর রিমুভ করবে
});

## Kursor.js এর বিভিন্ন Type:

আপনি type: 1 ব্যবহার করেছেন, যেখানে type এর মান ১-৫ পর্যন্ত দেওয়া যায়:

type: 1 → বেসিক কার্সর
type: 2 → বাউন্সিং কার্সর
type: 3 → ব্লার ইফেক্ট
type: 4 → গ্রোথ কার্সর
type: 5 → রিং কার্সর

আপনার যদি আরও কাস্টমাইজেশন দরকার হয়, জানাতে পারেন! [WordPress Naimur](https://github.com/Naimurrahmannahid/)
