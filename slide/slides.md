---
theme: default
background: https://source.unsplash.com/collection/94734566/1920x1080
class: text-center
highlighter: shiki
lineNumbers: false
drawings:
  persist: false
transition: slide-left
title: Thu hoạch môn Triết học
---

# Thu hoạch môn Triết học
Ứng dụng triết học trong AI Prompting

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Bấm Space để bắt đầu <carbon:arrow-right class="inline"/>
  </span>
</div>

---

# Thành viên nhóm

<v-clicks>

- Trần Ngọc Trung (tntrngtrung@gmail.com)
- Tạ Quang Bửu (taquangbuu01121999@gmail.com)
- Khang (khang23mse23133@fsb.edu.vn)
- Lâm (lamtt9341@gmail.com)
- Tuấn (@tuanpmt)
- Nguyễn Công Thắng
- BBB

</v-clicks>

---

# Nội dung

<v-clicks>

1. Giới thiệu chủ đề
2. Phát triển Prompts
   - Quá trình điều chỉnh
   - Kết quả AI
   - Phân tích triết học
3. Đánh giá
   - Ưu điểm
   - Hạn chế
   - Nguyên nhân
   - Giải pháp
4. Kết luận

</v-clicks>

---
layout: image-right
image: https://source.unsplash.com/collection/94734566/1920x1080
---

# Chủ đề của nhóm

<v-clicks>

- Chủ đề: [Điền chủ đề ở đây]
- Mục tiêu:
  - ...
  - ...
- Phạm vi:
  - ...
  - ...

</v-clicks>

---
layout: two-cols
---

# Phát triển Prompts

<v-clicks>

- Prompt 1:
  ```
  [Nội dung Prompt 1]
  ```
- Kết quả:
  ```
  [Kết quả AI 1]
  ```
- Phân tích:
  - ...
  - ...

</v-clicks>

<v-clicks>

- Prompt 2:
  ```
  [Nội dung Prompt 2]
  ```
  Hãy đóng vai một chuyên gia về công nghệ AI, quản trị doanh nghiệp, và triết học , và thực hiện một phân tích chi tiết về sự thay đổi của lực lượng sản xuất trong doanh nghiệp Call Center và CSKH (ví dụ như doanh nghiệp Google) khi AI được áp dụng.
  ```
- Kết quả:
  ```
  - Tư Liệu Sản Xuất (máy móc, công cụ, công nghệ) – Công Nghệ AI Thay Đổi Công Cụ Lao Động:
    + AI Chatbots & Voicebots: Các hệ thống như Google Duplex, ChatGPT, Amazon Lex có thể thực hiện các cuộc gọi, trả lời tin nhắn và hỗ trợ khách hàng mà không cần con người.
    + Hệ Thống Xử Lý Ngôn Ngữ Tự Nhiên (NLP): AI giúp hiểu và phân tích các câu hỏi khách hàng, sau đó phản hồi nhanh chóng và chính xác.
    + Tự Động Hóa Quy Trình Công Việc (RPA – Robotic Process Automation): Hỗ trợ xử lý yêu cầu đơn giản như xác minh danh tính, đặt lịch hẹn, tra cứu thông tin, giúp tiết kiệm thời gian và nhân lực.
  - Sức Lao Động (con người, trí thức, kỹ năng) – Con Người Chuyển Dịch Vai Trò :
    + Từ Công Việc Lặp Lại → Công Việc Giá Trị Cao: Nhân viên CSKH sẽ tập trung vào các tình huống phức tạp hơn. Chuyển từ người trả lời trực tiếp sang người giám sát AI, đảm bảo chatbot hoạt động chính xác và nâng cấp trải nghiệm khách hàng.
    + Từ Nhân Viên Bị Động → Chuyên Gia Cố Vấn: Thay vì chỉ phản hồi, nhân viên CSKH cần có kỹ năng đồng cảm, tư duy sáng tạo, và xử lý tình huống linh hoạt để bổ sung vào các lỗ hổng của AI.
    Kết quả: Công việc của con người trong ngành Call Center dần chuyển từ lao động tay chân sang lao động tri thức, đòi hỏi nhiều kỹ năng hơn.
  ```
- Điều chỉnh thêm trong prompt:
  - AI chỉ đơn thuần là một công cụ trong tư liệu sản xuất, hay có thể trở thành một yếu tố mới trong lực lượng sản xuất?
    Kết quả:
      + Có khả năng AI không chỉ là tư liệu sản xuất, mà còn có thể trở thành một "lực lượng sản xuất" mới vì nó có thể thực hiện chức năng mà trước đây chỉ có con người mới làm được – tạo ra giá trị kinh tế một cách độc lập.
      + So sánh AI Với Sức Lao Động Truyền Thống :
          |Tiêu chí	                      |Sức lao động con người	                      |AI|
          |Học hỏi và phát triển kỹ năng	|Cần đào tạo, mất thời gian thích nghi	      |Tự học qua dữ liệu, nhanh hơn nhiều|
          |Tạo ra giá trị kinh tế	        |Có khả năng sáng tạo và tư duy	              |Bắt đầu có khả năng thay thế tư duy logic|
          |Phụ thuộc vào con người	      |Có ý thức, cảm xúc, cần động lực làm việc	  |Hoạt động tự động, không cần động lực|
          |Tính linh hoạt	                |Thích ứng với nhiều lĩnh vực	                |Đang dần đa nhiệm nhờ AI tổng hợp (AGI)|
          |Khả năng mở rộng	              |Giới hạn bởi sức khỏe và thời gian	          |Có thể mở rộng vô hạn (Cloud AI)|
      + Tóm lại, AI đang trở thành một lực lượng sản xuất mới, nhưng chúng ta cần kiểm soát AI để tránh sự bất bình đẳng kinh tế quá mức.  
  - ...

</v-clicks>

::right::

<v-clicks>

# Điều chỉnh

- Lý do điều chỉnh:
  - ...
  - ...
- Áp dụng triết học:
  - ...
  - ...

</v-clicks>

---

# Đánh giá kết quả

<v-clicks>

## Ưu điểm
- ...
- ...

## Hạn chế
- ...
- ...

## Giải pháp
- ...
- ...

</v-clicks>

---
layout: center
class: text-center
---

# Cảm ơn đã lắng nghe
Câu hỏi & Thảo luận?
