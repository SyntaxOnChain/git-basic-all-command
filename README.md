# Git All Commands – Full Class Notes (Bash + CMD + Git)

এই রিপোজিটরিতে Git শেখার জন্য প্রয়োজনীয় প্রায় সব কমান্ড, টিউটোরিয়াল এবং প্র্যাকটিক্যাল উদাহরণ দেওয়া হয়েছে। এখানে Linux/macOS (Bash), Windows CMD এবং Git সম্পর্কিত ১৩টি ক্লাস কাভার করা হয়েছে।

---

## 📂 Included Files

| File Name                 | Description                                      |
| ------------------------- | ------------------------------------------------ |
| **git_all_commands.md**   | Markdown ফরম্যাটে টেক্সট-বেসড গাইড এবং রেফারেন্স |
| **git_all_commands.html** | HTML ফরম্যাটে স্টাইলসহ পূর্ণ কোর্স ম্যাটেরিয়াল   |

---

## 📚 Covered Classes & Topics

1. **Bash Command Reference** (pwd, ls, mkdir, cd, rm, touch, etc.)
2. **CMD Command Reference** (dir, cls, mkdir, echo, del, etc.)
3. **File/Folder Management Practical**
4. **Git Configuration Commands**
5. **Git Config View & Modify**
6. **First Git Project & Status Tracking**
7. **Git Add, Restore & Diff Practical**
8. **Git Workflow & Recovery**
9. **Git Commit, Log & Uncommit Rules**
10. **Git + HTML Project (VS Code)**
11. **Git Checkout & File Revert**
12. **.gitignore Explained with Examples**
13. **Git Alias for Shortcut Commands**

---

## 💡 How to Use

bash

# Clone the repository

[ If you want to clone this repo please click here](https://github.com/SyntaxOnChain/git-basic-all-command)

# অথবা GitHub-এ ডাউনলোড ZIP করে এক্সট্র্যাক্ট করুন

HTML ফাইলটি ওপেন করতে:

Double-click on git_all_commands.html

Markdown ফাইলটি দেখতে:

Open with VS Code / Typora / any Markdown viewer

---

## 🙋‍♂️ Created By

**Shujan Mahmud**  
📧 shujanrovy9797@gmail.com

---

## 📢 License

এই প্রজেক্টটি শিক্ষামূলক কাজে ব্যবহারের জন্য উন্মুক্ত। কপি করে শেয়ার করতে পারেন — শুধু ক্রেডিট দিন 😊

## Class3.1 - Bash (Linux/macOS) Command Reference

| Git Command                                    | Explanation                  | Example / Use Case      |
| ---------------------------------------------- | ---------------------------- | ----------------------- |
| pwd                                            | বর্তমান ফোল্ডার দেখায়        | pwd                     |
| ls                                             | ফাইল ও ফোল্ডার লিস্ট         | ls                      |
| ls -a                                          | হিডেনসহ সব ফাইল দেখায়        | ls -a                   |
| mkdir learn                                    | নতুন ফোল্ডার বানায়           | mkdir learn             |
| cd learn                                       | learn ফোল্ডারে ঢোকে          | cd learn                |
| cd ..                                          | এক ধাপ পেছনে যায়             | cd ..                   |
| rm -r learn                                    | learn ফোল্ডার সহ মুছে ফেলে   | rm -r learn             |
| touch test1.txt                                | খালি ফাইল তৈরি করে           | touch test1.txt         |
| echo "Shujan Mahmud, 28 years old" > test1.txt | লেখা বসিয়ে ফাইলে সংরক্ষণ     | echo "..." > test1.txt  |
| cat test1.txt                                  | ফাইলের লেখা দেখায়            | cat test1.txt           |
| rm test1.txt                                   | ফাইল ডিলিট করে               | rm test1.txt            |
| mkdir html css js react                        | একসাথে একাধিক ফোল্ডার বানায়  | mkdir html css js react |
| rm -r html css js react                        | একসাথে ফোল্ডারগুলো ডিলিট করে | rm -r html css js react |
| clear                                          | টার্মিনাল পরিষ্কার করে       | clear                   |

## Class3.2 - CMD (Windows Command Prompt) Command Reference

| Git Command                                    | Explanation                                             | Example / Use Case      |
| ---------------------------------------------- | ------------------------------------------------------- | ----------------------- |
| dir                                            | বর্তমান ফোল্ডারের কন্টেন্ট দেখায়                        | dir                     |
| cls                                            | স্ক্রিন পরিষ্কার করে                                    | cls                     |
| cd notes                                       | notes ফোল্ডারে ঢোকে                                     | cd notes                |
| cd ..                                          | এক ধাপ পেছনে যায়                                        | cd ..                   |
| mkdir notes                                    | নতুন notes ফোল্ডার তৈরি করে                             | mkdir notes             |
| mkdir test1 test2 test3                        | একসাথে ৩টা ফোল্ডার তৈরি করে                             | mkdir test1 test2 test3 |
| rmdir test1                                    | test1 ফোল্ডার ডিলিট করে                                 | rmdir test1             |
| echo > index.html                              | খালি ফাইল তৈরি করে                                      | echo > index.html       |
| type nul > index2.html                         | অন্যভাবে খালি ফাইল তৈরি করে                             | type nul > index2.html  |
| echo > day1.txt                                | খালি day1.txt তৈরি করে                                  | echo > day1.txt         |
| type nul > day2.txt                            | খালি day2.txt তৈরি করে                                  | type nul > day2.txt     |
| echo Hello We are Learning Commands > day1.txt | ফাইলে লেখে, আগের লেখা মুছে                              | echo ... > day1.txt     |
| echo I Love Bangladesh > day1.txt              | ফাইলের আগে লেখাগুলো মুছে নতুন লেখে                      | echo ... > day1.txt     |
| type day1.txt                                  | ফাইলের লেখা দেখায়                                       | type day1.txt           |
| echo I Love Pakistha >> day1.txt               | আগের লেখার শেষে নতুন লাইন যোগ করে                       | echo ... >> day1.txt    |
| del index.html                                 | index.html ফাইল ডিলিট করে                               | del index.html          |
| rmdir /s day1.txt                              | ভুলভাবে ফাইল ডিলিট করতে চেয়েছে (ফাইল নয় ফোল্ডারের জন্য) | rmdir /s day1.txt       |
| start code index.html                          | ফাইলটি VS Code এ খোলে                                   | start code index.html   |

## Class 3.3 : Practical File & Folder Management in Bash

| Command                                        | Explanation                                             | Example / Use Case                                |
| ---------------------------------------------- | ------------------------------------------------------- | ------------------------------------------------- |
| mkdir learn                                    | learn নামে একটি নতুন ফোল্ডার তৈরি করে                   | ওয়েব ডেভেলপমেন্ট শেখার জন্য আলাদা ফোল্ডার তৈরি    |
| cd learn                                       | learn ফোল্ডারে প্রবেশ করে                               | ফোল্ডারের ভিতরে ফাইল ম্যানেজমেন্ট চালাতে          |
| ls                                             | বর্তমান ফোল্ডারের সকল ফাইল ও ফোল্ডার দেখায়              | ফোল্ডারে কি আছে তা জানার জন্য                     |
| touch test1.txt                                | test1.txt নামে একটি খালি ফাইল তৈরি করে                  | পরীক্ষার জন্য একটি টেক্সট ফাইল তৈরি করতে          |
| ls                                             | test1.txt তৈরি হয়েছে কিনা তা যাচাই করে                  | ফাইল লিস্টে নতুন ফাইল আছে কি না দেখার জন্য        |
| mkdir html css js react                        | একসাথে html, css, js, react নামে চারটি ফোল্ডার তৈরি করে | ওয়েব ডেভেলপমেন্ট প্রজেক্ট স্ট্রাকচার তৈরি করতে    |
| rm -r html css js react                        | সবগুলো ফোল্ডার রিকার্সিভভাবে মুছে ফেলে                  | স্ট্রাকচার পরিবর্তনের সময় পুরনো ফোল্ডার মুছে ফেলা |
| rm test1.txt                                   | test1.txt ফাইলটি ডিলিট করে                              | যদি ফাইলটি আর দরকার না হয়                         |
| touch test1.txt                                | আবার test1.txt নামে ফাইল তৈরি করে                       | নতুন ডেটা রাখার জন্য প্রস্তুত ফাইল তৈরি           |
| echo "Shujan Mahmud, 28 years old" > test1.txt | test1.txt ফাইলে নির্দিষ্ট ডেটা লিখে                     | ব্যক্তিগত ইনফো সংরক্ষণ করার জন্য                  |
| cat test1.txt                                  | test1.txt ফাইলের ভিতরের ডেটা প্রদর্শন করে               | ফাইলে ঠিকমতো ডেটা সংরক্ষিত হয়েছে কিনা তা চেক করতে |

## Class 4: Git Configuration Commands

| Command                                                   | Explanation                               | Example / Use Case                                     |
| --------------------------------------------------------- | ----------------------------------------- | ------------------------------------------------------ |
| git version                                               | ইন্সটলকৃত Git-এর ভার্সন চেক করে           | নিশ্চিত হতে চাই যে Git সঠিকভাবে ইনস্টল হয়েছে           |
| git config --global user.name "shujan Mahmud"             | Git-এর জন্য গ্লোবাল ইউজার নেম সেট করে     | প্রথমবার Git সেটআপ করার সময় নিজের নাম সংরক্ষণ          |
| git config --global user.email "shujanrovy9797@gmail.com" | Git-এর জন্য গ্লোবাল ইমেইল ঠিকানা সেট করে  | GitHub বা অন্য প্ল্যাটফর্মে সঠিক পরিচয় সংরক্ষণের জন্য  |
| git config --global --list                                | বর্তমান গ্লোবাল কনফিগারেশনগুলো দেখায়      | নিশ্চিত হতে চাই যে নাম ও ইমেইল সঠিকভাবে সংরক্ষিত হয়েছে |
| git config --global user.name "mahmud Shujan"             | পূর্বের নাম পরিবর্তন করে নতুন নাম সেট করে | নাম ভুল হলে ঠিক করার জন্য                              |
| git config --global user.name "Shujan Mahmud"             | নাম আবার আপডেট করে ঠিক করে                | নিজের পছন্দ অনুযায়ী সঠিক নাম রাখার জন্য                |
| git config --global --list                                | সবশেষ পরিবর্তিত কনফিগারেশনগুলো আবার দেখায় | নাম ও ইমেইল সঠিকভাবে আপডেট হয়েছে কিনা তা চেক করা       |
| git config --global user.name                             | শুধুমাত্র গ্লোবাল ইউজার নেমটি দেখায়       | বর্তমানে কোন নাম সেট আছে তা জানার জন্য                 |
| git config --global user.email                            | শুধুমাত্র গ্লোবাল ইমেইলটি দেখায়           | বর্তমানে কোন ইমেইল সেট আছে তা জানার জন্য               |

## Class 5: Git Config View & Modify Commands

| Command                                       | Explanation                                                      | Example / Use Case                                        |
| --------------------------------------------- | ---------------------------------------------------------------- | --------------------------------------------------------- |
| git config --list                             | Git-এর সব স্তরের (local, global, system) কনফিগারেশন একসাথে দেখায় | দেখতে চাই কনফিগে কী কী সেটিংস আছে                         |
| git config --local --list                     | শুধু লোকাল (প্রজেক্ট নির্ভর) কনফিগারেশনগুলো দেখায়                | একটা নির্দিষ্ট রিপোজিটরিতে কী সেটিংস আছে তা চেক করার জন্য |
| git config --global --list                    | শুধু গ্লোবাল কনফিগারেশন দেখায় (সকল প্রজেক্টে প্রযোজ্য)           | ব্যক্তিগত ইউজার তথ্য ও সাধারণ সেটিংস চেক করার জন্য        |
| git config --system --list                    | সিস্টেম লেভেলের (কম্পিউটার ওয়াইড) কনফিগারেশন দেখায়               | Git ইন্সটলেশনের সময় যে সেটিংস হয় তা যাচাইয়ের জন্য         |
| git config --global --unset user.name         | গ্লোবাল ইউজার নেম মুছে ফেলে                                      | নতুন নাম দেওয়ার আগে পুরনোটা রিমুভ করার জন্য               |
| git config --global --list                    | পরিবর্তনের পর আপডেট হওয়া গ্লোবাল সেটিংস দেখায়                    | নিশ্চিত হতে চাই যে নাম মুছে গেছে                          |
| git config --global user.name "Shujan Mahmud" | নতুন গ্লোবাল ইউজার নেম সেট করে                                   | সঠিক নাম দিয়ে Git পরিচয় ঠিক করার জন্য                     |
| git config --global --list                    | নাম সেট হওয়ার পর সেটা আবার যাচাই করে                             | নিশ্চিত হওয়া যে পরিবর্তন সফল হয়েছে                        |
| start .gitconfig                              | Windows-এ গ্লোবাল কনফিগ ফাইল (gitconfig) খুলে দেখায়              | ম্যানুয়ালি কনফিগ ফাইল এডিট বা চেক করার জন্য               |

## Class 6: Git Project Practical Commands

| Command           | Explanation                              | Example / Use Case                        |
| ----------------- | ---------------------------------------- | ----------------------------------------- |
| pwd               | বর্তমান লোকেশন বা ফোল্ডার দেখায়          | আমি এখন কোথায় কাজ করছি সেটা জানবো         |
| ls                | বর্তমান ফোল্ডারে থাকা ফাইল/ফোল্ডার দেখায় | এই ফোল্ডারে কী আছে তা দেখতে               |
| cd desktop        | ডেস্কটপ ফোল্ডারে ঢোকে                    | ডেস্কটপে কাজ শুরু করতে চাই                |
| ls                | ডেস্কটপে থাকা আইটেম দেখায়                | ফোল্ডার ও ফাইল আছে কিনা দেখি              |
| clear             | টার্মিনাল পরিষ্কার করে (Linux/macOS)     | আগের কমান্ড ক্লিয়ার করে ফ্রেশ শুরু করতে   |
| ctrl + l          | টার্মিনাল ক্লিয়ার করার শর্টকাট           | কীবোর্ড শর্টকাটে পরিষ্কার করার জন্য       |
| mkdir notes       | নতুন "notes" ফোল্ডার তৈরি করে            | নতুন প্রজেক্ট স্টোর করার জন্য             |
| cd notes          | notes ফোল্ডারে ঢোকে                      | সেখানেই কাজ শুরু করতে চাই                 |
| ls                | notes ফোল্ডারে কিছু আছে কিনা দেখে        | ফাইল তৈরি না করলে খালি দেখাবে             |
| ls -a             | সব ফাইল (including hidden) দেখায়         | .git ফাইল দেখা যাবে Git init এর পর        |
| git init          | Git রিপোজিটরি তৈরি করে                   | ভার্সন কন্ট্রোল শুরু করতে চাই             |
| ctrl + l or clear | টার্মিনাল পরিষ্কার করার শর্টকাট          | ভিজুয়ালি পরিষ্কার রাখতে                   |
| ls -a             | .git সহ সব ফাইল/ফোল্ডার দেখায়            | Git সফলভাবে কাজ করছে কিনা দেখি            |
| touch day1.txt    | একটি খালি ফাইল তৈরি করে                  | প্রথম দিনের কাজ রেকর্ড করার জন্য          |
| start day1.txt    | Windows-এ ফাইল ওপেন করে                  | টেক্সট এডিটর দিয়ে লিখবো                   |
| open day1.txt     | macOS-এ ফাইল ওপেন করে                    | Mac ব্যবহারকারী হলে ওপেন করার জন্য        |
| ls -a             | সকল ফাইল/ফোল্ডারসহ দেখায়                 | day1.txt তৈরির পরে ফাইল আছে কিনা দেখি     |
| git status        | Git-এ ট্র্যাকড/আনট্র্যাকড ফাইল দেখায়     | day1.txt ফাইল Git দেখছে কিনা দেখি         |
| clear             | টার্মিনাল ক্লিয়ার করে                    | আবার পরিষ্কার শুরু করতে চাই               |
| touch day2.txt    | আরেকটি খালি ফাইল তৈরি করে                | দ্বিতীয় দিনের জন্য আলাদা ফাইল             |
| start day2.txt    | Windows-এ ফাইল ওপেন করে                  | লিখতে চাইলে টেক্সট এডিটর খুলবো            |
| open day2.txt     | macOS-এ ফাইল ওপেন করে                    | Mac এ কাজ করার জন্য                       |
| git status        | Git রিপোজিটরির বর্তমান অবস্থা দেখায়      | day2.txt ফাইল Git-এ দেখা যাচ্ছে কিনা দেখি |

## Class 7: Git Add, Restore, Diff Practical

| Command                                                           | Explanation                 | Example / Use Case             |
| ----------------------------------------------------------------- | --------------------------- | ------------------------------ |
| ls                                                                | ফাইল/ফোল্ডার লিস্ট করে      | কী কী ফাইল আছে দেখতে           |
| ctrl + l or clear                                                 | টার্মিনাল পরিষ্কার করে      | ক্লিন টার্মিনাল প্রয়োজন        |
| cd notes                                                          | notes ফোল্ডারে প্রবেশ করে   | প্রজেক্ট ফোল্ডারে ঢুকি         |
| ls -a                                                             | হিডেন সহ সব ফাইল দেখায়      | .git আছে কিনা দেখি             |
| start day1.txt                                                    | Windows-এ ফাইল ওপেন করে     | লিখতে চাইলে ওপেন করি           |
| open day1.txt                                                     | macOS-এ ফাইল ওপেন করে       | Mac ব্যবহারকারীর জন্য          |
| git status                                                        | Git-এর বর্তমান অবস্থা দেখায় | কোন ফাইল পরিবর্তিত বুঝি        |
| ctrl + l or clear                                                 | টার্মিনাল পরিষ্কার করে      | পরবর্তী ধাপ শুরু করি           |
| git add day1.txt                                                  | day1.txt স্টেজ করে          | কমিটের জন্য প্রস্তুত করি       |
| git add day2.txt                                                  | day2.txt স্টেজ করে          | কমিটের আগে অ্যাড করি           |
| git add .                                                         | সব পরিবর্তিত ফাইল অ্যাড করে | সব ফাইল একবারে স্টেজ করতে      |
| git status                                                        | স্টেজ হওয়া ফাইল দেখি        | অবস্থা যাচাই করি               |
| start day1.txt [write somthing and close]                         | ফাইলে কিছু লিখি ও সেভ করি   | পরিবর্তন যাচাই করার জন্য       |
| open day1.txt [write somthing and close]                          | Mac-এ একই কাজ               | Mac এ পরিবর্তন করি             |
| git status                                                        | পরিবর্তনের আপডেট দেখি       | নতুন পরিবর্তন দেখা যাচ্ছে কিনা |
| git add day1                                                      | ভুলভাবে স্টেজ করার চেষ্টা   | day1.txt না লিখলে error        |
| git status                                                        | কী স্টেজ হলো তা দেখি        | ভুলটা বুঝি                     |
| start day2.txt [write somthing and close]                         | day2.txt তে লিখি ও সেভ করি  | পরিবর্তন টেস্ট করার জন্য       |
| open day2.txt [write somthing and close]                          | Mac-এ একই কাজ               | Mac ইউজারের জন্য               |
| git status                                                        | পরিবর্তিত ফাইল দেখি         | stage হলো কিনা জানি            |
| git restore day2.txt [open the day2.txt file then see the change] | ফাইলের পরিবর্তন বাতিল করে   | আগের অবস্থায় ফিরে যাই          |
| git rm cached day2.txt                                            | স্টেজ থেকে সরিয়ে দেয়        | কমিট না করেই বাদ দিতে চাই      |
| git status                                                        | ফাইল স্টেজ আছে কিনা দেখি    | সফলভাবে unstaged হলো কিনা      |
| start day1.txt [open the day2.txt file then see]                  | দেখি restore এর পর কী হলো   | Windows এ যাচাই করি            |
| open day1.txt [open the day2.txt file then see]                   | Mac এ একই কাজ               | Mac ইউজার যাচাই করে            |
| git add day2.txt                                                  | আবার স্টেজে যোগ করি         | পরবর্তী কমিটের জন্য            |
| git status                                                        | স্টেজ অবস্থা যাচাই          | day2.txt যোগ হলো কিনা দেখি     |
| start day1.txt [write somthing and close]                         | আরও কিছু লিখি day1.txt-তে   | পরিবর্তনের জন্য                |
| open day1.txt [write somthing and close]                          | Mac এ একইভাবে               | Mac ইউজারও লিখে                |
| git status                                                        | পরিবর্তন দেখা যাচ্ছে কিনা   | আরও লিখার পর চেক করি           |
| ctrl + l or clear                                                 | টার্মিনাল ক্লিন করি         | ভিজুয়ালি পরিষ্কার করি          |
| git diff                                                          | স্টেজ না করা পরিবর্তন দেখায় | কী পরিবর্তন হয়েছে বুঝি         |
| git status                                                        | বর্তমান গিট অবস্থা দেখি     | সবকিছু প্রস্তুত কিনা জানি      |
| git add day1.txt                                                  | পরিবর্তিত ফাইল স্টেজ করি    | commit এর জন্য প্রস্তুত করি    |
| git status                                                        | ফাইনাল অবস্থা দেখি          | কমিটের আগে যাচাই               |

## Class 8: Git Restore, Diff & Stage Workflow

| Command                                                                                       | Explanation (বাংলায়)                  | Example / Use Case                           |
| --------------------------------------------------------------------------------------------- | ------------------------------------- | -------------------------------------------- |
| mkdir my-notes                                                                                | নতুন ফোল্ডার তৈরি করে                 | প্রজেক্ট ফোল্ডার তৈরি করার জন্য              |
| cd my-notes                                                                                   | my-notes ফোল্ডারে ঢোকে                | সেই ফোল্ডারে কাজ করার জন্য                   |
| ls                                                                                            | ফোল্ডারের সব ফাইল দেখায়               | ফোল্ডারে কী আছে সেটা দেখার জন্য              |
| ls -a                                                                                         | হিডেন ফাইলসহ সব ফাইল দেখায়            | .git বা অন্য হিডেন ফাইল আছে কিনা জানার জন্য  |
| git init                                                                                      | গিট রিপোজিটরি শুরু করে                | ফোল্ডারটিকে Git ট্র্যাক করতে শুরু করে        |
| ls -a                                                                                         | .git ফোল্ডার দেখা যায় কিনা চেক করে    | Git ইনিশিয়াল হয়েছে কিনা দেখার জন্য           |
| touch day1.txt                                                                                | নতুন ফাইল তৈরি করে                    | প্রথম দিনের কাজের ফাইল তৈরি                  |
| start day1.txt [Open and write somthing]                                                      | Windows-এ ফাইল ওপেন করে               | লিখা শুরু করার জন্য                          |
| open day1.txt [Open and write somthing]                                                       | macOS-এ ফাইল ওপেন করে                 | Mac ব্যবহারকারীদের জন্য                      |
| git status                                                                                    | পরিবর্তন আছে কিনা দেখায়               | Git ফাইল খুঁজে পেয়েছে কিনা                   |
| git add day1.txt                                                                              | day1.txt স্টেজে আনে                   | কমিটের জন্য প্রস্তুত                         |
| clear or ctrl + l                                                                             | টার্মিনাল পরিষ্কার করে                | নতুন করে কাজ শুরু করার জন্য                  |
| git status                                                                                    | ফাইল স্টেজে আছে কিনা দেখায়            | পরবর্তী স্টেপে যাওয়ার আগে নিশ্চিত হওয়ার জন্য |
| start day1.txt [Open and write somthing and see that whice will be change]                    | ফাইলে কিছু পরিবর্তন করা হয়            | Git কীভাবে পার্থক্য ধরছে বোঝার জন্য          |
| open day1.txt [Open and write somthing and see that whice will be change]                     | Mac ইউজারদের জন্য একই কাজ             | Mac কম্প্যাটিবল কাজ                          |
| git status                                                                                    | পরিবর্তনের আপডেট দেখায়                | unstaged changes আছে কিনা জানার জন্য         |
| git diff                                                                                      | কি পরিবর্তন হয়েছে তা দেখায়            | exact কি কি লাইন পরিবর্তন হয়েছে              |
| git status                                                                                    | পরিবর্তন স্টেজড নাকি না, সেটা জানায়   | কমিটের জন্য কি প্রস্তুত?                     |
| git restore day1.txt                                                                          | পরিবর্তন বাতিল করে দেয়                | আগের অবস্থা ফিরিয়ে আনে                       |
| start day1.txt [Open and write somthing and see that whice will be change and write somthing] | ফাইল আবার লিখে পরিবর্তন করা হয়        | নতুন কনটেন্ট লিখে দেখার জন্য                 |
| open day1.txt [Open and write somthing and see that whice will be change and write somthing]  | Mac ইউজারদের জন্য একই কাজ             | Mac ব্যবহারকারীদের জন্য                      |
| git status                                                                                    | সব পরিবর্তন এখন কোন অবস্থায় আছে দেখায় | unstaged changes আছে কিনা জানার জন্য         |
| git add day1.txt                                                                              | day1.txt স্টেজে আনে                   | কমিটের জন্য প্রস্তুত করা হয়                  |
| clear or ctrl + l                                                                             | টার্মিনাল পরিষ্কার করে                | পরবর্তী ধাপের প্রস্তুতি                      |
| git status                                                                                    | সব ফাইল কমিটের জন্য রেডি কিনা দেখায়   | সর্বশেষ কনফার্মেশন                           |

## Class 9: Git Commit, Log & Uncommit Rules

| Command                                                | Explanation (বাংলায়)                    | Note                          |
| ------------------------------------------------------ | --------------------------------------- | ----------------------------- |
| cd my_notes                                            | my_notes ফোল্ডারে প্রবেশ                |                               |
| git status                                             | Git স্টেটাস দেখায়                       | Untracked বা committed অবস্থা |
| git commit -m "day1 data is added"                     | Day1 এর ডেটা কমিট                       | 🔒 প্রথম কমিট                 |
| clear                                                  | টার্মিনাল পরিষ্কার                      | অথবাCtrl + L                  |
| git status                                             | নতুন ফাইল আছে কিনা দেখে                 |                               |
| touch day2.txt                                         | নতুন ফাইল তৈরি                          | 🆕 দ্বিতীয় দিনের কাজ          |
| open / start day2.txt                                  | ফাইল ওপেন করে কিছু লেখো, তারপর বন্ধ করো | Windows:start, Mac:open       |
| git status                                             | ফাইল Untracked দেখাবে                   |                               |
| git add day2.txt                                       | ফাইল স্টেজে যোগ হয়                      |                               |
| git status                                             | ফাইল এখন Staged                         |                               |
| git commit -m "day2 data is added"                     | Day2 এর ডেটা কমিট                       | 📌 দ্বিতীয় কমিট               |
| git status                                             | স্টেটাস আবার চেক                        |                               |
| git log                                                | কমিট হিস্টোরি দেখায়                     | ⏳ Day1 ও Day2 থাকবে          |
| touch day3.txt                                         | Day3 এর জন্য ফাইল তৈরি                  | ✅ এবার error হবে না          |
| git add day3.txt                                       | staging এ ফাইল যোগ                      |                               |
| open / start day3.txt                                  | ফাইল খুলে কিছু লিখো ও বন্ধ করো          |                               |
| git status                                             | ফাইলের পরিবর্তন দেখাবে                  |                               |
| git add day3.txt && git commit -m "day3 data is added" | একসাথে add ও commit                     | 🧠 Efficient                  |
| git status                                             | সব কিছু clean দেখাবে                    |                               |
| 🔁 Uncommit Rules (কমিট বাতিল বা পরিবর্তনের নিয়ম)      |
| :Q                                                     | vim/git log থেকে বের হতে                | 🔚 Quit command               |
| git reset --hard HEAD^                                 | শেষ কমিট ও কোড মুছে দেয়                 | ⚠️ সাবধান: কোডও হারায়         |
| git log                                                | কমিট হিস্টোরি চেক                       |                               |
| git reset --soft HEAD^                                 | শেষ কমিট বাতিল, কিন্তু কোড থাকে         | ✅ safer fallback             |
| git status                                             | Unstaged ফাইল দেখাবে                    |                               |
| git log                                                | কমিট ইতিহাস দেখা                        |                               |
| git commit -m "Day2 data is added"                     | ফাইল আবার কমিট                          | 🔁 পুনরায় সংরক্ষণ             |
| clear                                                  | টার্মিনাল পরিষ্কার                      |                               |
| git status                                             | স্টেটাস চেক                             |                               |
| git log                                                | শেষ কমিট দেখা                           |                               |
| git reset HEAD^                                        | শেষ কমিট soft reset হয়                  | Commit বাতিল, কোড অক্ষত       |
| git status                                             | Staged ফাইল এখন Unstaged                |                               |
| git add .                                              | সব ফাইল stage করা হয়                    | .মানে সব ফাইল                 |
| git commit -m "Day2 data is added"                     | সব ফাইল আবার কমিট                       | ✔️ টাইপো ঠিক করা              |
| git log                                                | ফাইনাল কমিট হিস্টোরি                    | 🔍 সব ক্লিয়ার                 |

## Class 10: VS Code + Git + HTML Project Workflow

| Command / Code                                                                                                                                                                                                                                                                        | Explanation (বাংলায়)                    | Note / Rules                          |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------- | ------------------------------------- |
| mkdir Learn_git                                                                                                                                                                                                                                                                       | "Learn_git" নামে একটি নতুন ফোল্ডার তৈরি | 📁 প্রজেক্টের মূল ফোল্ডার             |
| cd Learn_git                                                                                                                                                                                                                                                                          | ফোল্ডারে প্রবেশ                         |                                       |
| code .                                                                                                                                                                                                                                                                                | VS Code এ ফোল্ডার ওপেন                  | 💡 Windows + VS Code                  |
| index.html                                                                                                                                                                                                                                                                            | ফাইল তৈরি করো                           | Right click → New File → index.html   |
| <!DOCTYPE html> <html lang="en"> <head> <meta charset="UTF-8"> <meta name="viewport" content="width=device-width, initial-scale=1.0"> <title>Git Class 10</title> </head> <body> <h1>Welcome to codding school</h1> </body> </html>                                                   | HTML এর বেসিক স্ট্রাকচার লিখো           | 📌 h1 ট্যাগে মূল শিরোনাম              |
| git init                                                                                                                                                                                                                                                                              | Git শুরু করার জন্য ইনিশিয়ালাইজ          | 🔃 Git Repo তৈরি                      |
| git add index.html                                                                                                                                                                                                                                                                    | index.html ফাইল Git এ stage করা         |                                       |
| git commit -m "Add basic HTML layout and heading"                                                                                                                                                                                                                                     | প্রথম কমিট করা                          | 📏 Min 50 characters, clear & concise |
| <!--   Rules:   1. Commit message clear and concise  [max 50 characters]   2. Commit often, but not too often   3. Imperative mode   4. Add description for the commit   5. Test Before Commiting --> <nav> <a href="#">Home</a> <a href="#">About</a> <a href="#">Contact</a> </nav> | Navbar যোগ করো HTML ফাইলে               | 🧭 Home, About, Contact               |
| git add .                                                                                                                                                                                                                                                                             | সব ফাইল একসাথে stage করা                | .মানে সব ফাইল                         |
| git commit -m "add navber feature" -m "- Implement navber featur" -m "- Add home about and contact option for navigaion"                                                                                                                                                              | Navbar এর কমিট করো                      | 📌 Multi-line commit message ✅       |
| git log --oneline                                                                                                                                                                                                                                                                     | ছোট আকারে কমিট হিস্টোরি                 | 🧾 Summary view                       |
| git log                                                                                                                                                                                                                                                                               | ডিটেইল কমিট হিস্টোরি                    | ⏳ All commits with message           |
| <footer> <p>copyright by Shujan Mahmud</p> </footer>                                                                                                                                                                                                                                  | Footer যোগ করো HTML ফাইলে               | 🔻 নিচে কপিরাইট                       |
| git add index.html                                                                                                                                                                                                                                                                    | footer সহ index.html stage করো          |                                       |
| git commit -m "Add footer feature" -m "Closes #1"                                                                                                                                                                                                                                     | কমিট করে Issue বন্ধ করো                 | ✅Closes #1দিয়ে Issue লিঙ্কড          |

## Class 11: Git History, Checkout & File Revert

| Command / Step                                                                                                                                                                                            | Explanation (বাংলায়)                  | Note / Purpose                         |
| --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------- | -------------------------------------- |
| pwd                                                                                                                                                                                                       | বর্তমান ডিরেক্টরি দেখায়               | 📌 Path যাচাই                          |
| mkdir notes2 && cd notes2                                                                                                                                                                                 | "notes2" ফোল্ডার তৈরি ও প্রবেশ        |                                        |
| git init                                                                                                                                                                                                  | Git ইনিশিয়ালাইজ করো                   | ✅ Git চালু                            |
| ls -a                                                                                                                                                                                                     | সব ফাইল দেখায় including hidden (.git) | 🕵️‍♂️ .git আছে কিনা নিশ্চিত হও            |
| touch test1.txt                                                                                                                                                                                           | নতুন ফাইল তৈরি                        |                                        |
| start test1.txt / open test1.txt                                                                                                                                                                          | ফাইল ওপেন করে কিছু লিখে সেভ করো       | 📝 প্রথম কন্টেন্ট                      |
| git status → git add test1.txt → git status                                                                                                                                                               | ফাইল stage করা                        | 🟢 Changes ready                       |
| git commit -m "fist commit"                                                                                                                                                                               | প্রথম কমিট করা                        | 📍 commit history শুরু                 |
| git log / git log --oneline                                                                                                                                                                               | কমিট হিস্টোরি দেখা                    | 🧾 hash ID দরকার                       |
| git show [first 7-digit commit ID]                                                                                                                                                                        | সেই কমিটের ডিটেইল দেখা                | 🔎 Specific commit details             |
| touch test2.txt                                                                                                                                                                                           | নতুন ফাইল                             |                                        |
| open/start test2.txt → write → save                                                                                                                                                                       | প্রথমবার লিখো                         |                                        |
| git add test2.txt → git status                                                                                                                                                                            | ফাইল stage করা                        |                                        |
| open/start test2.txt → write more → save                                                                                                                                                                  | staged ফাইলে আবার পরিবর্তন            | ⚠️ unstaged changes                    |
| git checkout test2.txt                                                                                                                                                                                    | পরিবর্তন বাতিল                        | ♻️ ফাইল আগের stage version এ ফিরে যায়  |
| git commit -m "second commit"                                                                                                                                                                             | দ্বিতীয় কমিট                          |                                        |
| git log                                                                                                                                                                                                   | সব কমিট দেখো                          |                                        |
| touch test3.txt → write → save                                                                                                                                                                            | test3 ফাইল তৈরি ও লিখো                |                                        |
| git add . && git commit -m "Third commit"                                                                                                                                                                 | সবকিছু একসাথে কমিট                    | ⏳ auto stage & commit                 |
| git log --oneline                                                                                                                                                                                         | ছোট আকারে কমিট তালিকা                 | ✂️ কমিট ID কপি সহজ                     |
| git show [commit ID]                                                                                                                                                                                      | নির্দিষ্ট কমিট এর ডিটেইল              |                                        |
| git checkout [second commit ID]                                                                                                                                                                           | পুরাতন কমিটে ফিরে যাওয়া               | 👣 Detached HEAD                       |
| git checkout master                                                                                                                                                                                       | আবার মূল master ব্রাঞ্চে ফিরে আসা     | 🚀 বর্তমান অবস্থায় ফিরে                |
| git checkout [first commit ID]                                                                                                                                                                            | সবচেয়ে পুরাতন অবস্থা                  |                                        |
| start test1.txt → write mistake → save                                                                                                                                                                    | পুরাতন কমিটে গিয়ে ভুল করে লিখো        |                                        |
| git add test1.txt → git commit -m "fourt commit"                                                                                                                                                          | ভুলসহ কমিট                            |                                        |
| git checkout master                                                                                                                                                                                       | আবার master এ ফেরত আসো                | ❌ আগের কমিটে করা পরিবর্তন হারিয়ে যাবে |
| ⚠️ Warning: git checkout master করলে আগের পরিবর্তন (যা অন্য commit থেকে করা হয়েছিল) হারিয়ে যেতে পারে। যদি সেই পরিবর্তন ধরে রাখতে চাও তাহলে নতুন একটা branch করে কাজ করতে হবে। Branching আমরা সামনে শিখবো। |

## Class 12: .gitignore ফাইল — Git-এ ফাইল ইগনোর করার নিয়ম

| কমান্ড                                                                                                                                                                                                                                                                     | কাজের ব্যাখ্যা                      | উদ্দেশ্য / টিপস                |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------- | ------------------------------ |
| .gitignoreফাইলটি একটি বিশেষ টেক্সট ফাইল যা Git ভার্সন কন্ট্রোল সিস্টেমে ব্যবহার করা হয়। এটি নির্দেশ করে যে কোন ফাইল বা ফোল্ডারগুলো Git-এর দ্বারাট্র্যাককরা হবে না। এই জন্য আমরা একটি `.gitignore` ফাইল তৈরি করি যেখানে লিখে দেই কোন ফাইল Git-এ যুক্ত হবে না।               |
| 📌 উদাহরণ:✅ index.html, style.css, script.js → ট্র্যাক হবে❌ node_modules/, .env, \*.log → ট্র্যাক হবে না                                                                                                                                                                 |
| 💬 .gitignore কিভাবে কাজ করে?কমিট করার সময় Git ইগনোর করা ফাইলগুলো বাদ দেয়ওই ফাইলগুলো রিপোজিটরিতে push হবে নাঅন্য ডেভেলপারদের সাথেও শেয়ার হবে না                                                                                                                            |
| 🎯 .gitignore কেন গুরুত্বপূর্ণ?✅ অপ্রয়োজনীয় ফাইল Git-এ যাবে না🔐 সিকিউর ফাইল (.env) সুরক্ষিত থাকবে📦 প্রজেক্ট হালকা ও গোছানো থাকবে👥 টিম কাজ করলে কনফ্লিক্ট কম হয়                                                                                                         |
| 👉 টিপস:.gitignoreফাইলটি সবসময় আপনার প্রজেক্টের রুট ফোল্ডারে রাখবেন।                                                                                                                                                                                                       |
| pwd                                                                                                                                                                                                                                                                        | বর্তমান ফোল্ডারের লোকেশন দেখায়      | কাজ কোথায় হচ্ছে তা বুঝে নাও    |
| mkdir git_practice                                                                                                                                                                                                                                                         | নতুন ফোল্ডার তৈরি করো               | নতুন Git প্র্যাকটিস প্রজেক্ট   |
| cd git_practice                                                                                                                                                                                                                                                            | ফোল্ডারের ভিতরে যাও                 | পজিশনিং ঠিক করো                |
| touch .env story.txt test1.txt test2.txt test3.txt                                                                                                                                                                                                                         | নতুন ফাইল তৈরি করো                  | ইগনোর ও ট্র্যাকিং টেস্টের জন্য |
| git init                                                                                                                                                                                                                                                                   | Git ইনিশিয়ালাইজ করো                 | প্রজেক্টে Git শুরু             |
| git status                                                                                                                                                                                                                                                                 | সব ফাইল ট্র্যাক হচ্ছে কিনা দেখো     | সব কিছু এখনই unstaged          |
| touch .gitignore                                                                                                                                                                                                                                                           | .gitignore ফাইল তৈরি করো            | যা Git-এ যাবে না তা লিস্ট করো  |
| start/open .gitignore                                                                                                                                                                                                                                                      | ফাইলটি ওপেন করো                     | নিয়ম লিখে দাও                  |
| # .gitignore ফাইলের কনটেন্ট node_modules/ # node_modules ফোল্ডার ইগনোর করবে .DS_Store # macOS সিস্টেম ফাইল .env # এনভায়রনমেন্ট ভেরিয়েবল ফাইল _.log # সব লগ ফাইল _.tmp # সব টেম্পোরারি ফাইল \*.txt # সব txt ফাইল ইগনোর !story.txt # story.txt বাদ থাকবে, এটাকে ট্র্যাক করবে |
| git status                                                                                                                                                                                                                                                                 | .gitignore অনুযায়ী Git আপডেট দেখাবে | শুধু story.txt থাকবে trackable |
| git add .gitignore story.txt                                                                                                                                                                                                                                               | শুধু দরকারি ফাইল যোগ করো            | ইগনোরকৃত ফাইল অ্যাড হবে না     |
| git commit -m "add .gitignore and story file"                                                                                                                                                                                                                              | কমিট করো                            | পরিষ্কার ম্যাসেজ দাও           |
| git status                                                                                                                                                                                                                                                                 | কোন ফাইল বাকি আছে কি না দেখো        | Clean working tree             |

## Class 13: Git Alias — নিজের মতো শর্টকাট কমান্ড

| কমান্ড                                                                                                                                               | কাজের ব্যাখ্যা                                                                                         | উদাহরণ / টিপস                                                                                           |
| ---------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------- |
| aliasহলো Git কমান্ডের শর্টকাট। যখন বারবার একই কমান্ড লিখতে হয়, তখন alias ব্যবহার করে সেটাকে সংক্ষেপে চালানো যায়। এটা সময় বাঁচায় এবং কাজের গতি বাড়ায়। | ধরো, তুমি বারবারgit statusলিখছো। এটা বড় কমান্ড। তুমি চাইলেgit sবাgit stটাইপ করে সেই একই কাজ করতে পারো। | ⚠️ মনে রেখো: alias শুধু শর্টকাট; এটা Git-এর built-in কমান্ড নয়। তাই ব্যবহারে সাবধানতা ও স্পষ্টতা দরকার। |
| git config --list                                                                                                                                    | Git কনফিগারেশন লিস্ট করে                                                                               | দেখো আগে কোনো alias আছে কি না                                                                           |
| git config --global alias.st status                                                                                                                  | git stমানেইgit status                                                                                  | shortcut বানানো                                                                                         |
| git config --global alias.s status                                                                                                                   | git sমানেইgit status                                                                                   | আরও ছোট করে                                                                                             |
| git s                                                                                                                                                | alias কাজ করছে কিনা যাচাই করো                                                                          | এখন এটাgit statusএর মতো কাজ করবে                                                                        |
| git st                                                                                                                                               | দ্বিতীয় alias টেস্ট করো                                                                                | শর্টকাট চালাও                                                                                           |
| git config --global alias.co checkout                                                                                                                | git coদিয়েgit checkout                                                                                 | আরও alias বানানো যায়                                                                                    |
| git config --global alias.cm "commit -m"                                                                                                             | git cm "msg"দিয়ে কমিট                                                                                  | সময় বাঁচে কমিটে                                                                                         |
