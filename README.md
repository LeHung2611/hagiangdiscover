<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Khám Phá Hà Giang</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f7f7f7;
      color: #333;
    }
    header {
      background-color: #00796b;
      color: white;
      text-align: center;
      padding: 1rem 0;
    }
    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 20px;
      padding: 20px;
    }
    .card {
      background-color: white;
      border-radius: 10px;
      overflow: hidden;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    .card img {
      width: 100%;
      height: auto;
    }
    .card-content {
      padding: 15px;
    }
    .card h3 {
      margin-top: 0;
      color: #00796b;
    }
  </style>
</head>
<body>
  <header>
    <h1>Khám Phá Hà Giang</h1>
    <p>Hành trình đến với vùng đất địa đầu Tổ quốc</p>
  </header>

  <section class="gallery">
    <div class="card">
      <img src="images/doc-tham-ma.jpg" alt="Dốc Thẩm Mã" />
      <div class="card-content">
        <h3>Dốc Thẩm Mã</h3>
        <p>Nơi kiểm tra lòng kiên trì của du khách với khúc cua hiểm trở, nhưng cảnh sắc hai bên lại đẹp nghẹt thở.</p>
      </div>
    </div>

    <div class="card">
      <img src="images/nha-cua-pao.jpg" alt="Nhà của Pao" />
      <div class="card-content">
        <h3>Nhà của Pao</h3>
        <p>Không gian yên bình giữa thung lũng Sủng Là, nổi bật với nét văn hóa người Mông và bối cảnh phim nổi tiếng.</p>
      </div>
    </div>

    <div class="card">
      <img src="images/dinh-thu-ho-vuong.jpg" alt="Dinh thự họ Vương" />
      <div class="card-content">
        <h3>Dinh thự họ Vương</h3>
        <p>Công trình độc đáo của “vua Mèo” Vương Chí Sình, hòa quyện kiến trúc Trung Hoa và Pháp giữa cao nguyên đá.</p>
      </div>
    </div>

    <div class="card">
      <img src="images/cot-co-lung-cu.jpg" alt="Cột cờ Lũng Cú" />
      <div class="card-content">
        <h3>Cột cờ Lũng Cú</h3>
        <p>Điểm cực Bắc thiêng liêng của Tổ quốc với lá cờ đỏ sao vàng tung bay giữa trời xanh.</p>
      </div>
    </div>

    <div class="card">
      <img src="images/pho-co-dong-van.jpg" alt="Phố cổ Đồng Văn" />
      <div class="card-content">
        <h3>Phố cổ Đồng Văn</h3>
        <p>Những ngôi nhà trình tường cổ kính, mái ngói âm dương, mang vẻ đẹp hoài cổ vùng cao nguyên đá.</p>
      </div>
    </div>

    <div class="card">
      <img src="images/hem-tu-san.jpg" alt="Hẻm Tu Sản" />
      <div class="card-content">
        <h3>Hẻm Tu Sản</h3>
        <p>Hẻm vực sâu nhất Đông Nam Á, kỳ vĩ với vách đá dựng đứng bên dòng sông Nho Quế xanh ngọc.</p>
      </div>
    </div>

    <div class="card">
      <img src="images/song-nho-que.jpg" alt="Sông Nho Quế" />
      <div class="card-content">
        <h3>Sông Nho Quế</h3>
        <p>Dòng sông uốn lượn như lụa xanh dưới chân đèo Mã Pí Lèng, cảnh sắc như tranh vẽ.</p>
      </div>
    </div>

    <div class="card">
      <img src="images/hoang-su-phi.jpg" alt="Ruộng bậc thang Hoàng Su Phì" />
      <div class="card-content">
        <h3>Ruộng bậc thang Hoàng Su Phì</h3>
        <p>Vẻ đẹp vàng óng mùa lúa chín, công sức của bao thế hệ người dân vùng cao kiến tạo nên tuyệt tác thiên nhiên.</p>
      </div>
    </div>

    <div class="card">
      <img src="images/cao-nguyen-da.jpg" alt="Cao nguyên đá Đồng Văn" />
      <div class="card-content">
        <h3>Cao nguyên đá Đồng Văn</h3>
        <p>Công viên địa chất toàn cầu với dấu tích hàng trăm triệu năm, kỳ vĩ và bí ẩn giữa đại ngàn phương Bắc.</p>
      </div>
    </div>
  </section>
</body>
</html>
