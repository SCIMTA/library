# Chapter 2: Tính toán song song không đồng nhất

## Mục lục

1. [Tính toán song song không đồng nhất](1.Introduction.md)
2. [Tại sao cần hơn nữa tốc độ xử lý và tính toán song song?](2.Why_more_speed_or_parallelism.md)
3. [Tăng tốc các ứng dụng thực tế](3.Speeding_up_real_applications.md)
4. [Thách thức trong lập trình song song](4.Challenges_in_parallel_programming.md)
5. [Các giao diện lập trình song song liên quan](5.Related_parallel_programming_interfaces.md)
6. [Mục tiêu tổng quát](6.Overarching_goals.md)
7. [Cấu trúc cuốn sách này](7.Organization_of_the_book.md)
8. References

## Tóm tắt

Song song dữ liệu đề cập đến hiện tượng mà công việc tính toán cần thực hiện trên các phần khác nhau của tập dữ liệu có thể được thực hiện độc lập với nhau và do đó có thể được thực hiện song song với nhau. Nhiều ứng dụng thể hiện một lượng lớn song song dữ liệu giúp chúng thích hợp cho việc thực thi song song có khả năng mở rộng. Do đó, điều quan trọng đối với các lập trình viên song song là phải làm quen với khái niệm song song dữ liệu và các cấu trúc ngôn ngữ lập trình song song để viết mã khai thác song song dữ liệu. Trong chương này, chúng ta sẽ sử dụng các cấu trúc ngôn ngữ CUDA C để phát triển một chương trình song song dữ liệu đơn giản.
