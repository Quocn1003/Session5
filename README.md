# Reset CSS

\*{
padding: 0;
margin: 0;
box-sizing: border-box;
}

# Độ ưu tiên:

    Từ bé đến lớn:
    element ==> class ==> id ==> !important

# Layout: thiết kế, bố cục các element theo ý muốn

    1.float
    2.position
    3.flex : Định dạng 1 chiều
        - Dùng để định dạng layout
        1. Khi 1 element có thuộc tính display:flex thì sẽ dùng các thuộc tính của flex
    4.grid : Định dạng 2 chiều
    5.rwd - responsive web design

# Position: định vị

    1. static : Trạng thái mặc định
    2. relative : Vị trí tương đối
        - Khi 1 element có thuộc tính position = relative thì nó sẽ lấy vị trí ban đầu làm gốc. Khi muốn căn chỉnh khối theo các chiều thì dùng
        top
        right
        left
        bottom
    3. absolute : Vị trí tuyệt đối
        - Sẽ ăn theo vị trí của thằng cha chứa nó gần nhất có thuộc tính là position ( khác static) thì sẽ lấy vị trí thằng cha làm gốc. Nếu không có thằng cha nào chứa nó thì sẽ ăn theo kích thước màn hình
    4. fixed
        - Công dụng: cố định element khi lăn chuột
    5. sticky
