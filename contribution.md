# Đóng góp vào dự án

**Dự án không thể thành công nếu không có sự đóng góp của cộng đồng. Nếu bạn muốn đóng góp một phần vào dự án, bạn vui lòng xem các công việc cần thực hiện [tại đây](https://github.com/aivivn/Machine-Learning-Yearning-Vietnamese-Translation/issues. Các công việc được gán nhãn [high priority](https://github.com/aivivn/Machine-Learning-Yearning-Vietnamese-Translation/issues?q=is%3Aissue+is%3Aopen+label%3A"high+priority") là các công việc cần được hoàn thành trước.**

Việc đóng góp được thực hiện qua các Pull Request. Đây là bài [hướng dẫn tạo pull request](https://codetot.net/contribute-github/) khá chi tiết, các bạn có thể tham khảo.

Lưu ý khi tạo Pull Requests:

* Kiểm tra trong [Issues](https://github.com/aivivn/Machine-Learning-Yearning-Vietnamese-Translation/issues) và [Pull Requests](https://github.com/aivivn/Machine-Learning-Yearning-Vietnamese-Translation/pulls) xem đã có ai đề cập hoặc làm việc đó chưa, tránh dẫm chân lên nhau.

* Khi bạn bắt đầu làm một việc mới, bạn để lại một comment ở issue tương ứng, hoặc tạo issue mới, hoặc tạo một Pull Request mới với tiêu đề tương ứng để những người làm sau không làm trùng công việc của bạn.


# Các bước dịch một chương
Một chương được hoàn thành khi nó trải qua các công đoạn:

## 1. Copy + format từ bản gốc
Để tiện cho việc dịch và review, mỗi chương bắt đầu với việc copy chương tương ứng từ [bản gốc](https://www.deeplearning.ai/machine-learning-yearning/) và định dạng theo markdown. Ví dụ như [ở đây](https://github.com/aivivn/Machine-Learning-Yearning-Vietnamese-Translation/pull/24/files).

Một vài lưu ý:
1. Tên chương để ở heading 1, ví dụ:

```
# 1. Why Machine Learning Strategy
->

```
2. Một đoạn trong bản gốc đưa về một dòng, ví dụ:
```
Machine learning is the foundation of countless important applications, including web search, email anti-spam, speech recognition, product recommendations, and more. I assume that you or your team is working on a machine learning application, and that you want to make rapid progress. This book will help you do so.
->

```

3. Sau mỗi dòng là một dấu mũi tên (`->`) và một dòng trắng để người dịch điền về sau. Người dịch bắt đầu ở dòng **dưới dấu mũi tên**. Ví dụ:
```
Your team has a lot of ideas, such as:
->
Đội của bạn có rất nhiều ý tưởng, chẳng hạn:
```

4. Các chữ in đậm, in nghiêng cần được định dạng như bản gốc, ví dụ:
```
**in đậm**
*in nghiêng*
```

## 2.Bổ sung bảng thuật ngữ
Sau khi copy từ bản gốc của một chương cần kiểm tra xem những từ nào trong chương đó chưa có trong [Bảng thuật ngữ](glossary.md). Nếu chưa có thì bổ sung bằng cách tạo một Pull Request.

## 3. Dịch
Sau khi đã có bản gốc và đầy đủ thuật ngữ, bạn có thể tạo một Pull Request mới để bắt đầu dịch. Chú ý, bạn chỉ dịch khi một thuật ngữ đã có trong [Bảng thuật ngữ](glossary.md) để hạn chế số lượng biến thể của một từ. Nếu một thuật ngữ chưa có trong Bảng thuật ngữ, bạn có thể tạo riêng một Pull Request để bổ sung.

## 4. Review
Khi có Pull Request mới, sẽ cần rất nhiều bình luận và kiểm tra trước khi Pull Request đó được approved.


## 5. Hoàn thành
Sau khi một Pull Request được approve, nhóm điều hành sẽ xóa phần tiếng Anh và các dấu `->`, chỉ để phần tiếng Việt trước khi merge và master branch.

# Làm thế nào để đóng góp vào việc dịch?
Trong năm bước bên trên, bạn có thể đóng góp ở bất cứ bước nào ngoại trừ bước cuối chỉ có nhóm điều hành mới được thực hiện. Mỗi bước nhỏ nên tạo một Pull Request riêng để thuận lợi cho việc Review.

Lưu ý: Mỗi Pull Request chỉ nên thực hiện một công việc duy nhất. Không nên gộp nhiều công việc vào một Pull Request.

**Mọi đóng góp của các bạn đều được lưu lại trong lịch sử của repo này.**
