# BÀI 2: Tối ưu Prompt - Giải nghĩa logic code Java

## 1. Nội dung Prompt sau khi tối ưu

Hãy giải thích ngắn gọn logic nghiệp vụ của hàm Java `checkLevel(int points)` bên dưới, tập trung vào các điều kiện rẽ nhánh và ý nghĩa giá trị trả về. Nếu `points >= 1000` thì hàm trả về gì, nếu không đạt điều kiện đó thì hàm trả về gì?

```java
public class MemberCheck {

    public static String checkLevel(int points) {

        if (points >= 1000) {

            return "VIP";

        }

        return "Standard";

    }

}
```

## 2. Đoạn phản hồi nhận được từ AI sau khi chạy thử prompt

Hàm `checkLevel(int points)` dùng để kiểm tra hạng thành viên của khách hàng dựa trên điểm tích lũy.

Logic của hàm gồm 2 trường hợp:

- Nếu `points >= 1000`, hàm trả về chuỗi `"VIP"`. Điều này có nghĩa là khách hàng có từ 1000 điểm trở lên sẽ được xếp hạng VIP.
- Nếu `points < 1000`, điều kiện trong câu lệnh `if` không đúng, nên hàm bỏ qua khối `if` và trả về chuỗi `"Standard"`. Điều này có nghĩa là khách hàng có dưới 1000 điểm sẽ được xếp hạng Standard.

Tóm lại, hàm này phân loại khách hàng thành 2 mức: **VIP** khi điểm tích lũy từ 1000 trở lên, và **Standard** khi điểm tích lũy dưới 1000.
