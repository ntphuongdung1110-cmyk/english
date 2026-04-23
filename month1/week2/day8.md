# Day 8 — Discussing Problems & Solutions
**Thứ Ba | Tháng 1, Tuần 2**
**Chủ đề:** Nói về vấn đề và đề xuất giải pháp — kỹ năng quan trọng nhất của QC Manager

---

## 🎬 YouTube Hôm Nay — Bấm Vào Nghe

| # | Video | Mục đích |
|---|---|---|
| 1 | [English Phrases — Problem Solving Professional](https://www.youtube.com/results?search_query=english+phrases+problem+solving+professional) | Phrases chính |
| 2 | [Business English — Meetings: Problems & Solutions](https://www.youtube.com/results?search_query=business+english+meetings+problems+solutions) | Context meetings thật |
| 🍿 | [Friends — English Clips](https://www.youtube.com/results?search_query=friends+english+learn+subtitles+clip) | Buổi tối — casual English + cười |

> **Cách dùng:** Xem cả 2. Chú ý cách họ nêu vấn đề → đề xuất giải pháp → confirm.

---

## ⏱️ Lịch 45 Phút

| Thời gian | Hoạt động |
|---|---|
| 00–05 | Anki ôn từ |
| 05–15 | Học từ vựng + mẫu câu |
| 15–25 | Nghe Brian / TED về problem-solving |
| 25–35 | Shadowing |
| 35–43 | Ghi âm: Roleplay — trình bày vấn đề và giải pháp trong meeting |
| 43–45 | Ghi notebook |

---

## 📚 Từ Vựng Hôm Nay — Problems & Solutions

### Mô Tả Vấn Đề
| Từ / Cụm | Phiên âm | Nghĩa | Ví Dụ |
|---|---|---|---|
| **raise a concern** | /reɪz ə kənˈsɜːrn/ | nêu lo ngại | I need to raise a concern about the test coverage. |
| **flag an issue** | /flæɡ ən ˈɪʃuː/ | báo hiệu vấn đề | I want to flag an issue before we proceed. |
| **come to light** | /kʌm tə laɪt/ | được phát hiện | A critical bug came to light during regression testing. |
| **stem from** | /stem frəm/ | xuất phát từ | This issue seems to stem from the recent API changes. |
| **have implications for** | /hæv ˌɪmplɪˈkeɪʃənz fər/ | ảnh hưởng đến | This bug has implications for user data integrity. |
| **impact** (verb) | /ˈɪmpækt/ | tác động đến | This defect impacts roughly 40% of users. |

### Đề Xuất Giải Pháp
| Từ / Cụm | Phiên âm | Nghĩa | Ví Dụ |
|---|---|---|---|
| **tackle** | /ˈtækəl/ | giải quyết (chủ động) | There are a few ways we can tackle this. |
| **address** | /əˈdres/ | xử lý/đề cập | We need to address this before the release. |
| **a viable option** | /ə ˈvaɪəbəl ˈɒpʃən/ | lựa chọn khả thi | One viable option is to delay go-live by 24 hours. |
| **I'd recommend** | /aɪd ˌrekəˈmend/ | tôi đề nghị | I'd recommend we do a hotfix rather than a full rollback. |
| **going forward** | /ˈɡoʊɪŋ ˈfɔːrwərd/ | từ nay về sau | Going forward, we should run regression after every deployment. |
| **in the meantime** | /ɪn ðə ˈmiːntaɪm/ | trong lúc đó | In the meantime, we can apply a workaround. |

---

## 🗣️ Mẫu Câu Hôm Nay

### Pattern 1: Nêu vấn đề rõ ràng
```
"I'd like to flag an issue with [area]. 
What we're seeing is [description], which [impact]."
→ I'd like to flag an issue with the payment flow. 
   What we're seeing is incorrect tax calculation, which impacts all orders above $500.
```

### Pattern 2: Phân tích nguyên nhân
```
"The root cause appears to be [cause]. 
This stems from [underlying reason]."
→ The root cause appears to be a logic error in the tax module. 
   This stems from the recent changes made in sprint 12.
```

### Pattern 3: Đề xuất giải pháp có lựa chọn
```
"I see two ways we can tackle this:
Option A: [first option] — the advantage is [benefit], but [downside].
Option B: [second option] — this is safer, though it [trade-off]."
→ I see two ways we can tackle this:
   Option A: Apply a quick fix and do a targeted regression — faster, but higher risk.
   Option B: Delay release by 24 hours and do a full regression — safer, but we miss the deadline.
```

### Pattern 4: Đưa ra recommendation cuối
```
"Given the risk, my recommendation is [option] because [reason]. 
Going forward, we should [preventive action]."
→ Given the risk to user data, my recommendation is Option B — a 24-hour delay. 
   Going forward, we should add tax calculation to our regression checklist.
```

### Pattern 5: Mở thảo luận
```
"I'm open to other suggestions. What does everyone think?"
"Does anyone see a different approach?"
"Happy to hear if there's a faster solution I'm not seeing."
```

---

## 🎧 Shadowing Script — Problem-Solving Meeting

```
"Okay, so I need to flag something important 
before we wrap up.

During today's regression testing, we came across 
an issue in the search feature. What we're seeing is 
results loading incorrectly when the user applies 
multiple filters at the same time.

Now, the root cause isn't fully clear yet, 
but it seems to stem from the filter logic 
that was updated in last week's deployment.

In terms of impact — it affects users on the 
advanced search page, which, based on our analytics, 
is about 25% of our active users.

So I see two options here. 
Option A — we patch it with a quick fix tonight 
and do a targeted test on just the search flow. 
Faster, but there's some risk we miss edge cases.

Option B — we delay the release by 24 hours, 
do a proper root cause analysis, 
and run a full regression pass.

My recommendation is Option B. 
The risk of shipping this is too high.
But I'm open to other views — what do you all think?"
```

---

## 💬 Speaking Prompt — Roleplay (Ghi Âm 3 Phút)

> **Tình huống:** Trong sprint review, bạn phát hiện 1 bug critical. PM hỏi: "What's the issue and what do you suggest we do?"

**Yêu cầu:**
- Nêu vấn đề rõ ràng (1 phút)
- Phân tích nguyên nhân (30 giây)
- Đưa ra 2 lựa chọn (1 phút)
- Recommendation + mở thảo luận (30 giây)

---

## ✍️ Notebook Hôm Nay

```
📅 Ngày 8 — Chủ đề: Problems & Solutions

✨ 3 cụm hay nhất:
   1. "_______________" → _______________
   2. "_______________" → _______________
   3. "_______________" → _______________

🎙️ Roleplay hôm nay:
   Vấn đề tôi nêu: _______________
   Solutions tôi đề xuất: _______________
   Ghi âm: ___ phút  |  Tự đánh giá: __/10

💡 Câu nào nghe chuyên nghiệp nhất? _______________
```
