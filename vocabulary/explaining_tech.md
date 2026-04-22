# Giải thích kỹ thuật cho người không biết tech

## Từ vựng cốt lõi

| Câu | Phiên âm | Nghĩa |
|---|---|---|
| In simple terms... | /ɪn ˈsɪmpəl tɜːrmz/ | Nói đơn giản... |
| Think of it like... | /θɪŋk əv ɪt laɪk/ | Hãy nghĩ nó như... |
| The way it works is... | /ðə weɪ ɪt wɜːrks ɪz/ | Cách hoạt động là... |
| Basically... / Essentially... | /ˈbeɪsɪkli / ɪˈsɛnʃəli/ | Về cơ bản... |
| The short version is... | /ðə ʃɔːrt ˈvɜːrʒən ɪz/ | Nói ngắn gọn là... |
| Without getting too technical... | /wɪˈðaʊt ˈɡɛtɪŋ tuː ˈtɛknɪkəl/ | Không cần đi sâu kỹ thuật... |
| Does that make sense so far? | /dʌz ðæt meɪk sɛns soʊ fɑːr/ | Đến đây có rõ không? |
| Let me use an analogy | /lɛt miː juːz ən əˈnælədʒi/ | Để tôi dùng một ví dụ tương tự |

## Khi bị hỏi về bug / lỗi

| Câu | Phiên âm | Nghĩa |
|---|---|---|
| The system behaved unexpectedly | /ðə ˈsɪstəm bɪˈheɪvd ˌʌnɪkˈspɛktɪdli/ | Hệ thống hoạt động không như mong đợi |
| It's doing X when it should do Y | /ɪts ˈduːɪŋ X wɛn ɪt ʃʊd duː Y/ | Nó đang làm X thay vì phải làm Y |
| This only happens when... | /ðɪs ˈoʊnli ˈhæpənz wɛn/ | Điều này chỉ xảy ra khi... |
| We've identified the root cause | /wiːv aɪˈdɛntɪfaɪd ðə ruːt kɔːz/ | Chúng tôi đã xác định nguyên nhân gốc |
| The fix is in progress | /ðə fɪks ɪz ɪn ˈprɒɡrɛs/ | Đang trong quá trình sửa |
| This is a known issue — we're tracking it | /ðɪs ɪz ə noʊn ˈɪʃuː — wiːr ˈtræktɪŋ ɪt/ | Đây là lỗi đã biết — chúng tôi đang theo dõi |

## Khi giải thích QC / Testing

| Câu | Phiên âm | Nghĩa |
|---|---|---|
| Testing ensures the product works as expected | /ˈtɛstɪŋ ɪnˈʃʊrz ðə ˈprɒdʌkt wɜːrks æz ɪkˈspɛktɪd/ | Testing đảm bảo sản phẩm hoạt động đúng |
| We test before release to catch issues early | /wiː tɛst bɪˈfɔːr rɪˈliːs tuː kætʃ ˈɪʃuːz ˈɜːrli/ | Chúng tôi test trước khi ra mắt để phát hiện lỗi sớm |
| A bug is when something doesn't work as designed | /ə bʌɡ ɪz wɛn ˈsʌmθɪŋ dʌzənt wɜːrk æz dɪˈzaɪnd/ | Bug là khi thứ gì đó không hoạt động như thiết kế |
| Regression means making sure old features still work | /rɪˈɡrɛʃən miːnz ˈmeɪkɪŋ ʃʊr oʊld ˈfiːtʃərz stɪl wɜːrk/ | Regression là đảm bảo tính năng cũ vẫn hoạt động |
| Automation runs tests automatically, like a robot | /ˌɔːtəˈmeɪʃən rʌnz tɛsts ˌɔːtəˈmætɪkli laɪk ə ˈroʊbɒt/ | Automation chạy test tự động, như một robot |

---

## Hội thoại mẫu — Giải thích bug cho stakeholder / PM

> **PM:** "What happened with the payment issue last night?"
>
> **Dung:** "So, without getting too technical — when a user applied a discount coupon, the system was calculating the total incorrectly. Think of it like a cashier entering the discount at the wrong step in the process. The result was that users were seeing the wrong price before checkout."
>
> **PM:** "How serious is it?"
>
> **Dung:** "It affected anyone using a coupon on mobile — that's about 30% of our checkout traffic. We've identified the root cause. The fix is already in progress and should be deployed by tonight."
>
> **PM:** "Will it happen again?"
>
> **Dung:** "We're adding an automated check to catch this going forward. So if something like this slips in again, our system will flag it before it reaches users."

---

## Hội thoại mẫu — Giải thích automation testing cho CEO

> **CEO:** "What exactly is test automation? Why does it take so long to set up?"
>
> **Dung:** "Great question. In simple terms, test automation is like teaching a robot to do the same repetitive checks that a human tester would do — clicking buttons, filling forms, verifying results — but much faster and consistently."
>
> **CEO:** "So why not just automate everything from day one?"
>
> **Dung:** "The setup takes time upfront, like training the robot. You need to write instructions for every scenario. But once it's done, it pays off — instead of 3 hours of manual testing per release, it takes 10 minutes automatically."
>
> **CEO:** "And how does this help us?"
>
> **Dung:** "It means we can release faster with more confidence. Fewer bugs reaching users, less time spent on repetitive work, and our QC team can focus on the complex cases that actually need human judgment."

---

## Hội thoại mẫu — Giải thích QC process cho người mới

> **New member:** "So what exactly does QC do?"
>
> **Dung:** "Basically, we're the last line of defense before the product reaches users. The way it works is: developers build the feature, then we test it to make sure it behaves exactly as designed — and catch anything that doesn't."
>
> **New member:** "What's the difference between a bug and a feature request?"
>
> **Dung:** "Good question. A bug is when something doesn't work as it was designed to. A feature request is when it works fine, but someone wants it to work differently. The distinction matters because bugs need to be fixed — feature requests go through planning."

---

## Analogy hay dùng

| Khái niệm | Analogy dễ hiểu |
|---|---|
| Regression testing | Kiểm tra lại toàn bộ xe sau khi sửa phanh |
| Automation | Dạy robot làm bài kiểm tra thay người |
| Bug | Công thức nấu ăn bị in sai bước |
| Staging environment | Buổi diễn tập trước khi lên sân khấu thật |
| Deployment | Giao hàng từ kho ra cửa hàng |
| API | Người phục vụ nhận order và chuyển vào bếp |
