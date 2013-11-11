200 Cụm văn bản tiếng Việt dùng cho tóm tắt đa văn bản
=============
Tác giả: Trần Mai Vũ, Vũ Trọng Hóa, Phí Văn Thủy, Lê Đức Trọng, Hà Quang Thụy<br>
Đơn vị: Phòng thí nghiệm Công nghệ tri thức, Đại học Công nghệ, ĐHQG Hà Nội<br>
Email liên hệ: vutranmai@gmail.com / vutm@vnu.edu.vn<br>
Đề tài: Thiết kế và cài đặt chương trình tóm tắt đa văn bản tiếng Việt, Đề tài cấp Bộ Giáo dục và Đào tạo(Mã số: B2012-01-24)<br>

--------------------------------------------------------------------------
+ Thông tin xây dựng: Quá trình xây dựng dữ liệu hoàn toàn thủ công. Có 2 bước để xây dựng tập dữ liệu:<br>
<ul>
	<li>Bước 1: Thu thập dữ liệu và tạo ra các cụm tài liệu (mỗi cụm chứa các tài liệu liên quan đến một vấn đề cụ thể), dữ liệu được thu thập từ trang web Baomoi và được phân bố đều trên tất cả các chủ đề của Baomoi (Khoảng 8-10 chủ đề chính: Thế giới, Xã hội, Văn hóa, Kinh tế, KH-CN, Thể thao, Giải trí, Pháp luật, Giáo dục, Sức khỏe, Ô tô - Xe máy, Nhà đất)</li>
	<li>Bước 2: Có 2 người tham gia vào việc xây dựng các bản tóm tắt tham chiếu. Việc tóm tắt có 2 công đoạn: Trích ra các câu quan trọng và viết lại thành một đoạn văn liền mạch</li>
	<li>Số lượng dữ liệu: 200 cụm</li>
</ul>
+ Từng thư mục tương ứng với 1 cụm tài liệu (2-5 tài liệu trong mỗi cụm, thường là 3), tên của thư mục là <id> của cụm<br>
+ Trong mỗi thư mục:<br>
<ul>
	<li><cluster_id>.info: chưa thông tin id cụm và nhãn cụm (nhãn cụm do người tạo ra cụm dựa vào nội dung để đưa ra)</li>
	<li><cluster_id>.ref1.txt: bản tham chiếu do người tóm tắt số 1</li>
	<li><cluster_id>.ref1.tok.txt: bản tham chiếu số 1 đã được tách câu và tách từ</li>
	<li><cluster_id>.ref2.txt: bản tham chiếu do người tóm tắt số 2</li>
	<li><cluster_id>.ref1.tok.txt: bản tham chiếu số 2 đã được tách câu và tách từ</li>
	<li><cluster_id>.sum.txt: bản tóm tắt do máy sinh ra</li>
	<li><cluster_id>.sum.tok.txt: bản tóm tắt do máy sinh ra đã được tách câu và tách từ</li>
Các file trong cùng thư mục là các tài liệu (tài liệu là bài báo điện tử) thuộc cụm:
	<li><document_id>.body.txt: Chứa phần nội dung chính của tài liệu</li>
	<li><document_id>.body.tok.txt: Chứa phần nội dung của tài liệu đã được tách câu và tách từ</li>
	<li><document_id>.info.txt: Chứa các thông tin khác về tài liệu như: được link, thời gian viết, tiêu đề của tài liệu và tóm tắt của tài liệu (tóm tắt này do người tạo ra tài liệu viết)</li>
</ul>
