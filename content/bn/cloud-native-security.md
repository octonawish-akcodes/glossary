---
title: ক্লাউড নেটিভ  নিরাপত্তা (Cloud Native Security)
status: Completed
category: ধারণা
---

## এটা কি

ক্লাউড নেটিভ সিকিউরিটি এমন একটি পদ্ধতি যা [ক্লাউড নেটিভ অ্যাপ্লিকেশন](/cloud-native-apps/) এ নিরাপত্তা তৈরি করে। এটি নিশ্চিত করে যে নিরাপত্তা উন্নয়ন থেকে উৎপাদন পর্যন্ত সমগ্র অ্যাপ্লিকেশন জীবনচক্রের অংশ। ক্লাউড নেটিভ সিকিউরিটি ক্লাউড নেটিভ এনভায়রনমেন্টের বিবরণ, যথা দ্রুত কোড পরিবর্তন এবং অত্যন্ত ক্ষণস্থায়ী অবকাঠামোর সাথে খাপ খাওয়ানোর সময় প্রথাগত নিরাপত্তা মডেলের মতো একই মান নিশ্চিত করতে চায়। ক্লাউড নেটিভ নিরাপত্তা [DevSecOps](/devsecops/) নামক অনুশীলনের সাথে অত্যন্ত সম্পর্কিত।

## এটা যেসব সমস্যাতে দৃষ্টিপাত করে

প্রথাগত নিরাপত্তা মডেলগুলি অনেকগুলি অনুমানের সাথে তৈরি করা হয়েছিল যা আর বৈধ নয়৷ ক্লাউড নেটিভ অ্যাপ্লিকেশানগুলি ঘন ঘন পরিবর্তিত হয়, প্রচুর সংখ্যক ওপেন সোর্স (Open-Source) টুল এবং লাইব্রেরি ব্যবহার করে, প্রায়শই বিক্রেতা-নিয়ন্ত্রিত পরিকাঠামোতে চালিত হয় এবং দ্রুত পরিকাঠামো পরিবর্তনের বিষয়। কোড পর্যালোচনা, দীর্ঘ মানের নিশ্চয়তা চক্র, হোস্ট-ভিত্তিক দুর্বলতা স্ক্যানিং, এবং শেষ মুহূর্তের নিরাপত্তা পর্যালোচনাগুলি ক্লাউড নেটিভ অ্যাপ্লিকেশনগুলির সাথে স্কেল (Scale) করতে পারে না।

## এটা কিভাবে সাহায্য করে

ক্লাউড নেটিভ সিকিউরিটি (Cloud Native Security)  কাজ করার একটি নতুন উপায় প্রবর্তন করে যা প্রথাগত নিরাপত্তা মডেল (security model) থেকে এমন একটিতে স্থানান্তরিত করে যেখানে রিলিজ চক্রের (release cycle) প্রতিটি ধাপে নিরাপত্তা জড়িত থাকে অ্যাপ্লিকেশনগুলিকে রক্ষা করে৷ ম্যানুয়াল অডিট (audit) এবং চেকগুলি মূলত স্বয়ংক্রিয় স্ক্যানগুলির সাথে প্রতিস্থাপিত হয়। দ্রুত কোড রিলিজ পাইপলাইনগুলি কম্পাইল (compile) করার আগে দুর্বলতার জন্য কোড স্ক্যান (scan)করে এমন সরঞ্জামগুলির সাথে একত্রিত করা হয়। ওপেন সোর্স (open-Source) লাইব্রেরিগুলি বিশ্বস্ত উৎস থেকে টেনে আনা হয় এবং দুর্বলতার জন্য পর্যবেক্ষণ করা হয়। ধীরগতির পরিবর্তনের পরিবর্তে একটি ক্লাউড নেটিভ নিরাপত্তা মডেল (Cloud Native Security Model) ঘন ঘন  হালনাগাদ করা দুর্বল উপাদানগুলির দ্বারা বা পরিকাঠামো নিয়মিতভাবে প্রতিস্থাপন করা নিশ্চিত করে এটিকে আলিঙ্গন করে।    
