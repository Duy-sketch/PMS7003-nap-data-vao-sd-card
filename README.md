# PMS7003-nap-data-vao-sd-card
Tạo ioc như hình

Khi tạo ioc nhớ chọn FATFS trong middleware sau đó làm gì cần thì e viết vào lười quá

cả mấy cái cấu hình gpio hay uart cần thì thêm sau cũng được

Generate code (nhớ gen file gpio.c uart.c riêng tại code main.c dùng vậy)

Thêm file Midware (nhớ phải chọn làm nguồn)

chỉnh sửa tất cả file gồm stm32f1xx_it.c, user_diskio.c.h gì đấy như mẫu

cuối cùng là chỉnh main.c r chạy thôi, nhớ cấp nguồn riêng 5V cho pms


