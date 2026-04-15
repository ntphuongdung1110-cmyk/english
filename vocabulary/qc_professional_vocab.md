# QC Professional Vocabulary — Master Reference
**Tham khảo nhanh khi cần từ chuyên môn QC bằng tiếng Anh**

---

## Nhóm 1: Testing Types

| Thuật Ngữ | Nghĩa | Ví Dụ Câu |
|---|---|---|
| **smoke test** | test nhanh xem build có chạy được không | Run a smoke test before full regression. |
| **sanity test** | test sau fix để verify | Quick sanity check after the hotfix. |
| **regression test** | test lại để đảm bảo không có lỗi mới | Full regression takes 2 days. |
| **exploratory test** | test sáng tạo, không theo script | Allocate time for exploratory testing. |
| **UAT** | User Acceptance Testing | Client UAT starts Monday. |
| **E2E test** | End-to-end, test toàn luồng | E2E covers the full checkout flow. |
| **integration test** | test tích hợp giữa các module | Integration tests caught 3 API issues. |
| **performance test** | test hiệu suất (load, stress, spike) | Performance testing under 1000 concurrent users. |
| **security test** | test bảo mật | Security test flagged a SQL injection risk. |
| **usability test** | test trải nghiệm người dùng | Usability test with 5 real users next week. |

---

## Nhóm 2: Defect & Bug Language

| Thuật Ngữ | Nghĩa | Ví Dụ Câu |
|---|---|---|
| **defect / bug** | lỗi | We logged 12 defects this sprint. |
| **severity** | mức độ nghiêm trọng (S1–S4) | This is Severity 1 — it crashes the app. |
| **priority** | mức độ ưu tiên xử lý | High priority — fix before Friday. |
| **critical / blocker** | chặn release | We have 2 blocker bugs open. |
| **reproduce** | tái hiện lỗi | I can reproduce this on iOS 17, step 3. |
| **root cause** | nguyên nhân gốc rễ | Root cause: null pointer exception in the auth module. |
| **regression** | lỗi cũ quay lại | This is a regression from last sprint. |
| **workaround** | cách xử lý tạm | There's a workaround but we need a proper fix. |
| **hotfix** | fix khẩn cấp sau release | We pushed a hotfix at 2am. |
| **known issue** | lỗi đã biết, chưa fix | This is a known issue — logged in backlog. |
| **false positive** | test báo lỗi nhưng thực ra không có | 3 of those were false positives. |
| **flaky test** | test không ổn định | This test is flaky — fails 30% of the time. |

---

## Nhóm 3: Process & Workflow

| Thuật Ngữ | Nghĩa | Ví Dụ Câu |
|---|---|---|
| **test plan** | kế hoạch kiểm thử | I'll have the test plan ready by Monday. |
| **test case** | kịch bản kiểm thử | We have 200 test cases for this feature. |
| **test suite** | bộ test cases | The regression suite covers 85% of core features. |
| **test coverage** | % được test | We're at 78% test coverage. |
| **acceptance criteria** | tiêu chí chấp nhận | Story is missing clear acceptance criteria. |
| **definition of done** | tiêu chí hoàn thành | QC sign-off is part of our definition of done. |
| **sign-off** | phê duyệt / chấp nhận | QC sign-off required before go-live. |
| **go-live / release** | phát hành sản phẩm | Go-live is scheduled for Friday 6pm. |
| **release candidate** | build dự kiến release | RC1 is ready for final testing. |
| **rollback** | quay lại phiên bản cũ | We had to rollback after the prod incident. |
| **deployment** | triển khai lên môi trường | Deployment to staging is complete. |
| **environment** | môi trường: dev/staging/prod | Tested on staging, not yet on prod. |

---

## Nhóm 4: Agile & Team Context

| Thuật Ngữ | Nghĩa | Ví Dụ Câu |
|---|---|---|
| **sprint** | chu kỳ phát triển (1–2 tuần) | We're in sprint 12 right now. |
| **backlog** | danh sách công việc chưa làm | This is in the backlog for next sprint. |
| **standup** | họp ngắn hằng ngày | I raise blockers in the daily standup. |
| **retrospective** | họp nhìn lại sau sprint | Retrospective is Friday afternoon. |
| **blocker** | thứ chặn tiến độ | I have a blocker — need dev input. |
| **velocity** | tốc độ của team | Team velocity dropped this sprint. |
| **shift left** | đưa QC vào sớm hơn | We're shifting left — QC from day one. |
| **shift right** | test trên môi trường production | Shift right: canary releases + monitoring. |
| **CI/CD** | tích hợp & triển khai liên tục | Tests run automatically in our CI/CD pipeline. |
| **automation coverage** | % test đã được tự động hóa | Automation coverage is currently 40%. |

---

## Nhóm 5: Reporting & Communication

| Thuật Ngữ | Nghĩa | Ví Dụ Câu |
|---|---|---|
| **bug escape rate** | % lỗi lọt qua QC ra production | Our bug escape rate is 2% this quarter. |
| **defect density** | số lỗi trên 1000 dòng code | Defect density improved by 15%. |
| **pass rate** | % test cases pass | 88% pass rate this sprint. |
| **mean time to detect (MTTD)** | thời gian trung bình phát hiện lỗi | MTTD decreased from 3 days to 1 day. |
| **mean time to resolve (MTTR)** | thời gian trung bình sửa lỗi | MTTR is currently 2.5 days. |
| **quality gate** | ngưỡng chất lượng tối thiểu để tiến | We failed the quality gate — can't proceed. |
| **risk-based testing** | test ưu tiên theo rủi ro | We use risk-based testing to prioritize. |
| **traceability matrix** | ma trận truy xuất requirements ↔ tests | Update the traceability matrix after changes. |
| **test summary report** | báo cáo tổng kết kiểm thử | I'll send the test summary report by EOD. |
| **incident report** | báo cáo sự cố | The incident report is due by end of week. |

---

## Nhóm 6: Sentences Bạn Cần Thuộc Lòng

```
1. "I'd like to flag a Severity-1 issue in the checkout flow before we proceed."
2. "The root cause appears to be a race condition in the payment module."
3. "My recommendation: delay go-live by 24 hours to run a targeted regression."
4. "As of this morning, 142 of 158 test cases have passed — that's a 90% pass rate."
5. "This looks like a regression from the changes deployed in sprint 11."
6. "We need to get to the bottom of why this edge case wasn't caught earlier."
7. "The bug escape rate this quarter is at 1.5% — down from 3.2% last quarter."
8. "I can reproduce this consistently on Android 14, step 3 of the registration flow."
9. "We're blocked on this until the API team provides the updated documentation."
10. "Quality isn't just QC's responsibility — it's baked into every step of our process."
```
