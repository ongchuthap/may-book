# Chính sách quyền riêng tư của Mây Book

Cập nhật lần cuối: 12 tháng 11 năm 2026. [English](privacy-policy.md)

Mây Book là ứng dụng đọc sách EPUB có trợ lý đọc AI tuỳ chọn, do một nhà phát triển độc lập làm ra. Chính sách này cho biết ứng dụng làm gì với dữ liệu của bạn.

Tóm tắt: nhà phát triển không chạy máy chủ nào và không nhận gì từ ứng dụng. Sách, ghi chú và các cuộc trò chuyện của bạn nằm trên thiết bị của bạn và trong iCloud của chính bạn. Văn bản chỉ được gửi tới nhà cung cấp AI hoặc dịch vụ tìm kiếm web khi bạn đã thiết lập dịch vụ đó bằng khoá của chính mình và đã cho phép trong ứng dụng.

## Nhà phát triển thu thập gì

Không gì cả. Ứng dụng không có tài khoản, không có phân tích, quảng cáo, theo dõi hay dịch vụ báo lỗi, và không bao giờ kết nối với máy chủ nào của nhà phát triển. Nếu bạn đã chọn chia sẻ dữ liệu phân tích với nhà phát triển ứng dụng trong cài đặt của thiết bị, Apple có thể chuyển báo cáo sự cố và số liệu sử dụng ẩn danh cho nhà phát triển; đó là lựa chọn giữa bạn và Apple.

## Dữ liệu của bạn nằm ở đâu

- **Trên thiết bị**, trong vùng lưu trữ riêng của ứng dụng: sách (file EPUB), vị trí đọc, highlight, ghi chú, thuật ngữ, các cuộc trò chuyện với AI, trí nhớ và bản tóm lược sách của AI, bản dịch và cài đặt.
- **Trong iCloud của bạn**, khi bật đồng bộ iCloud: file sách nằm trong thư mục của ứng dụng trên iCloud Drive, phần còn lại nằm trong các file thuộc vùng chứa iCloud của ứng dụng, để các thiết bị khác của bạn nhận được. Apple giữ chúng dưới Tài khoản Apple của bạn; nhà phát triển không xem được.
- **Khoá API** được giữ trong iCloud Keychain (được mã hoá, chỉ đồng bộ giữa các thiết bị của bạn). Khoá không bao giờ được ghi vào file trên iCloud Drive và không bao giờ được gửi cho nhà phát triển.
- **Spotlight và widget**: tên sách được đưa vào Spotlight trên thiết bị của bạn; highlight và ghi chú chỉ khi bạn bật tuỳ chọn đó, trên từng thiết bị. Widget hiện sách đang đọc và thời gian đọc từ một bản sao giữ trên thiết bị.
- **Phông chữ, đọc to và dịch nhanh** chạy trên thiết bị: phông chữ đi kèm ứng dụng, đọc to dùng giọng đọc của hệ thống, còn dịch từ ngắn dùng bản dịch trên máy của Apple trước.

## Những gì được gửi tới nhà cung cấp AI bạn chọn

Các tính năng AI chỉ hoạt động sau khi bạn thêm khoá API (hoặc địa chỉ máy chủ của chính bạn) cho một nhà cung cấp AI: OpenRouter, DeepSeek, OpenAI, hoặc bất kỳ máy chủ tương thích OpenAI nào bạn nhập. Trước lần đầu tiên gửi bất cứ thứ gì tới một nhà cung cấp, ứng dụng hiện một màn hình nêu tên nhà cung cấp, liệt kê những gì sẽ được gửi và xin phép bạn. Chỉ khi bạn cho phép, ứng dụng mới gửi cho nhà cung cấp đó:

- câu hỏi của bạn và cuộc trò chuyện trong chuỗi hội thoại;
- các đoạn trong sách: đoạn bạn chọn, và những đoạn AI đọc hoặc tìm trong sách để trả lời; tên sách, tác giả và vị trí bạn đang đọc;
- ghi chú, highlight và thuật ngữ của bạn, khi AI tra cứu chúng;
- trí nhớ của AI về cuốn sách và về bạn (ghi chú và tóm tắt các cuộc trò chuyện trước), kèm mỗi câu hỏi về cuốn sách đó;
- hướng dẫn bạn viết cho AI;
- văn bản bạn nhờ dịch hoặc giải thích, kể cả những từ thiết bị không dịch được, và các chương hiện ở chế độ song ngữ;
- chạy nền: bản tóm lược mỗi cuốn sách bạn nhập (mục lục và khoảng 6.000 từ trích từ sách), và bản tóm tắt các cuộc trò chuyện cho trí nhớ của AI.

OpenRouter chuyển yêu cầu tới công ty làm ra mô hình bạn chọn. Một máy chủ bạn chạy ngay trên cùng thiết bị (địa chỉ như `localhost`) nhận yêu cầu mà không cần màn hình xin phép, vì không có gì rời khỏi thiết bị.

Bạn chọn nhà cung cấp và giữ tài khoản với họ, và ứng dụng chỉ gửi những gì tính năng bạn đang dùng cần đến. Nhà cung cấp xử lý những gì họ nhận được theo điều khoản và chính sách quyền riêng tư của họ, mà bạn đã chấp nhận khi tạo tài khoản và khoá; nhà phát triển không có thoả thuận nào với các nhà cung cấp và không nhận dữ liệu này. Hãy đọc chính sách của nhà cung cấp trước khi cho phép chia sẻ.

## Những gì được gửi tới dịch vụ tìm kiếm và các trang web

Khi công cụ web của AI đang bật và bạn đã thiết lập một dịch vụ tìm kiếm (Tavily, Brave Search, Exa, DeepSeek hoặc máy chủ SearXNG của bạn), sau khi bạn cho phép, ứng dụng gửi cho dịch vụ đó các truy vấn tìm kiếm mà AI viết ra từ câu hỏi của bạn; với bản tóm lược sách, truy vấn chứa tên sách và tác giả. AI cũng có thể mở các trang web từ kết quả tìm kiếm hoặc từ đường link bạn gửi, cũng chỉ sau khi bạn cho phép: các trang web đó thấy địa chỉ mạng (IP) của thiết bị và trang được yêu cầu. Khi dịch vụ tìm kiếm là DeepSeek, DeepSeek mở các trang đó thay cho ứng dụng và thấy địa chỉ của chúng.

## Cách rút lại sự cho phép

- **Cài đặt › Riêng tư › Chia sẻ dữ liệu với AI** liệt kê mọi nhà cung cấp và dịch vụ bạn đã cho phép. Ngừng chia sẻ với một nơi tại đó: không gì được gửi tới nơi đó nữa, và công việc chạy nền cho nơi đó dừng ngay. Ứng dụng sẽ hỏi lại trước khi gửi bất cứ thứ gì mới.
- Bạn cũng có thể tắt trí nhớ của AI (Cài đặt › Cách agent dạy), tắt công cụ web (Cài đặt › Công cụ của agent) hoặc xoá khoá (Cài đặt › Nhà cung cấp AI).
- Dữ liệu mà nhà cung cấp hoặc dịch vụ tìm kiếm đã nhận được giữ theo quy định lưu trữ của họ; hãy xoá trong tài khoản của bạn với công ty đó.

## Lưu giữ và xoá dữ liệu

- Xoá một cuốn sách trong ứng dụng sẽ xoá highlight, ghi chú, các cuộc trò chuyện, trí nhớ và bản tóm lược của sách đó, trên mọi thiết bị có đồng bộ.
- Trong phần trí nhớ của một cuốn sách, bạn có thể sửa hoặc xoá những gì AI nhớ; từng cuộc trò chuyện đều xoá được.
- Để xoá bản sao trên iCloud, hãy xoá thư mục của ứng dụng trong iCloud Drive và dữ liệu của ứng dụng trong phần dung lượng iCloud của Tài khoản Apple.
- Xoá ứng dụng sẽ xoá mọi thứ ứng dụng đã lưu trên thiết bị, trừ khoá vẫn nằm trong iCloud Keychain: hãy xoá khoá trong Cài đặt › Nhà cung cấp AI trước khi xoá ứng dụng.
- Nhà phát triển không giữ dữ liệu nào về bạn. Nếu bạn gửi email cho nhà phát triển (hỗ trợ, hoặc "Báo lỗi câu trả lời này"), email chỉ được dùng để xem xét báo cáo và trả lời bạn, và được xoá khi xong việc.

## Báo lỗi

"Báo lỗi câu trả lời này" mở ứng dụng thư với một thư gửi nhà phát triển, gồm câu trả lời và tên mô hình, tên nhà cung cấp. Không gì được gửi đi nếu bạn không tự gửi thư đó.

## Trẻ em

Ứng dụng không thu thập dữ liệu cá nhân của bất kỳ ai, kể cả trẻ em.

## Thay đổi

Khi chính sách này thay đổi, phiên bản mới được đăng tại đây với ngày mới, và ứng dụng hiện phiên bản đi kèm với nó.

## Liên hệ

[mike.infra.dev@gmail.com](mailto:mike.infra.dev@gmail.com)
