<div align="center">

<img src="./assets/icons/meikova.png" width="96" height="96" alt="Meikova Logo" />

# MEIKOVA

**Build what matters.**  
*Hệ sinh thái phần mềm mã nguồn mở đa nền tảng, kiến trúc Ambient Dark và trải nghiệm Offline-First.*

<p align="center">
  <img src="https://img.shields.io/badge/License-MIT-9EF6D0?style=flat-square&labelColor=11151B" alt="License MIT" />
  <img src="https://img.shields.io/badge/Architecture-Offline--First-83E8AC?style=flat-square&labelColor=11151B" alt="Offline-First" />
  <img src="https://img.shields.io/badge/SSO-Ed25519-A6C5FF?style=flat-square&labelColor=11151B" alt="Ed25519 SSO" />
  <img src="https://img.shields.io/badge/Design-Ambient%20Instrument-FFB38A?style=flat-square&labelColor=11151B" alt="Ambient Instrument" />
  <img src="https://img.shields.io/badge/Zero-Tracking%20%7C%20Telemetry-92DDD4?style=flat-square&labelColor=11151B" alt="Zero Tracking" />
</p>

---

</div>

## Triết Lý Phát Triển & Sứ Mệnh Cộng Đồng

Meikova được xây dựng với mục tiêu cung cấp bộ giải pháp phần mềm độc lập, mã nguồn mở, bảo vệ quyền riêng tư và phục vụ công việc hàng ngày của người dùng trên mọi nền tảng:

- **Mã nguồn mở vì cộng đồng:** 100% mã nguồn minh bạch, giấy phép MIT, không gắn mã theo dõi (zero analytics/telemetry), tự do tự lưu trữ (self-hostable) và làm chủ dữ liệu cá nhân.
- **Tiện ích thực chiến hàng ngày:** Tối ưu cho nhu cầu thực tế: hòa trộn âm thanh, thu nhận nội dung đa phương tiện, quản lý tài chính, truy cập máy tính từ xa, duyệt tệp tin bảo mật và giám sát an ninh mạng.
- **Đa nền tảng thống nhất:** Trải nghiệm liền mạch trên Windows, macOS, Linux, Android, iOS, Web PWA, Browser Extension và OS Background Services.
- **Offline-First & Hiệu năng cao:** Dữ liệu luôn lưu trữ cục bộ (Local SQLite WAL / Turso LibSQL Cloud Sync), khởi động dưới 1 giây, độ trễ tiệm cận 0ms và không phụ thuộc kết nối Internet liên tục.

---

## Bảng Nhận Diện 26 Thương Hiệu (Folded Continuum)

Toàn bộ hệ thống sản phẩm thuộc Meikova được chuẩn hóa dựa trên ngôn ngữ hình học **Folded Continuum** – nguyên lý hai thùy và giao điểm lemniscate không lặp lại:

<div align="center">
  <img src="./assets/meikova-identity-board.png" width="100%" alt="Meikova 26 Marks - One Continuum Identity Board" />
</div>

---

## 4 Trụ Cột Nền Tảng Cốt Lõi (Core Ecosystem)

Bốn giải pháp nền tảng định hình khung kiến trúc phân tán của hệ sinh thái Meikova:

<table>
  <thead>
    <tr>
      <th width="70" align="center">Icon</th>
      <th width="200">Dự Án</th>
      <th>Mô Tả & Trọng Tâm Kỹ Thuật</th>
      <th width="140">Nền Tảng</th>
      <th width="110" align="center">Trạng Thái</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center">
        <a href="https://github.com/Meikova/meikova-auth">
          <img src="./assets/icons/meikova-auth.png" width="56" height="56" alt="Meikova Auth" />
        </a>
      </td>
      <td>
        <a href="https://github.com/Meikova/meikova-auth"><strong>Meikova Auth</strong></a><br />
        <code>meikova-auth</code>
      </td>
      <td>
        <strong>Identity Gateway & Universal SSO Gateway.</strong><br />
        Cổng xác thực tập trung, xác minh Ed25519 offline (~0.1ms), PBKDF2/scrypt, Google OAuth 2.0 GIS đa nền tảng, tích hợp Turso LibSQL Cloud.
      </td>
      <td>Web SSO, Cloud REST, JWKS</td>
      <td align="center"><img src="https://img.shields.io/badge/Status-Active%20Dev-A6C5FF?style=flat-square&labelColor=11151B" alt="Active Dev" /></td>
    </tr>
    <tr>
      <td align="center">
        <a href="https://github.com/Meikova/meikova-relay">
          <img src="./assets/icons/meikova-relay.png" width="56" height="56" alt="Meikova Relay" />
        </a>
      </td>
      <td>
        <a href="https://github.com/Meikova/meikova-relay"><strong>Meikova Relay</strong></a><br />
        <code>meikova-relay</code>
      </td>
      <td>
        <strong>Duplex Bridge Remote Control.</strong><br />
        Hệ thống điều khiển máy trạm từ xa và đường hầm đo xa (telemetry tunnel) độ trễ siêu thấp. Khách truy cập web client zero-install, truyền tải dữ liệu an toàn qua WebSocket.
      </td>
      <td>Desktop (Win/Linux/macOS), Web PWA</td>
      <td align="center"><img src="https://img.shields.io/badge/Release-v1.0.53-83E8AC?style=flat-square&labelColor=11151B" alt="v1.0.53" /></td>
    </tr>
    <tr>
      <td align="center">
        <a href="https://github.com/Meikova/meikova-loop">
          <img src="./assets/icons/meikova-loop.png" width="56" height="56" alt="Meikova Loop" />
        </a>
      </td>
      <td>
        <a href="https://github.com/Meikova/meikova-loop"><strong>Meikova Loop</strong></a><br />
        <code>meikova-loop</code>
      </td>
      <td>
        <strong>Phase Rotor AI Audio Mashup Deck.</strong><br />
        Bộ máy mashup âm thanh thời gian thực, tách stem Demucs (Vocals/Drums/Bass/Other), bộ lọc DSP, Web Audio API Canvas Visualizer và soundscape player liên tục.
      </td>
      <td>Web PWA, Desktop, Mobile, HF Space</td>
      <td align="center"><img src="https://img.shields.io/badge/Release-v1.0.3-FFB38A?style=flat-square&labelColor=11151B" alt="v1.0.3" /></td>
    </tr>
    <tr>
      <td align="center">
        <a href="https://github.com/Meikova/meikova-harvest">
          <img src="./assets/icons/meikova-harvest.png" width="56" height="56" alt="Meikova Harvest" />
        </a>
      </td>
      <td>
        <a href="https://github.com/Meikova/meikova-harvest"><strong>Meikova Harvest</strong></a><br />
        <code>meikova-harvest</code>
      </td>
      <td>
        <strong>Gravity Intake Media Engine.</strong><br />
        Công cụ thu nhận và trích xuất đa phương tiện hiệu năng cao. Hỗ trợ đa luồng tải, chuyển đổi FFmpeg, stream capture, bypass kiểm duyệt qua Google DoH.
      </td>
      <td>Desktop Shell, Web, Chrome Extension</td>
      <td align="center"><img src="https://img.shields.io/badge/Release-v2.0.7-83C4FF?style=flat-square&labelColor=11151B" alt="v2.0.7" /></td>
    </tr>
  </tbody>
</table>

---

## Dự Án Ứng Dụng Đang Phát Triển (Domain Extensions)

Các công cụ ứng dụng tiện ích chuyên sâu phục vụ đời sống, công việc kỹ thuật và quản lý dữ liệu:

<table>
  <thead>
    <tr>
      <th width="70" align="center">Icon</th>
      <th width="200">Dự Án</th>
      <th>Đặc Tả Nghiệp Vụ & Nền Tảng Kỹ Thuật</th>
      <th width="140">Stack Chính</th>
      <th width="110" align="center">Trạng Thái</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center">
        <a href="https://github.com/Meikova/meikova-balance">
          <img src="./assets/icons/meikova-balance.png" width="56" height="56" alt="Meikova Balance" />
        </a>
      </td>
      <td>
        <a href="https://github.com/Meikova/meikova-balance"><strong>Meikova Balance</strong></a><br />
        <code>meikova-balance</code>
      </td>
      <td>
        <strong>Reserve Fold Personal Finance.</strong><br />
        Quản lý tài chính cá nhân thông minh, phân tích thu chi đa tiền tệ, bóc tách hóa đơn tự động qua AI cục bộ, theo dõi danh mục tài sản và dự toán ngân sách.
      </td>
      <td>TypeScript, SQLite, Local AI, PWA</td>
      <td align="center"><img src="https://img.shields.io/badge/Status-In%20Dev-ECD39A?style=flat-square&labelColor=11151B" alt="In Dev" /></td>
    </tr>
    <tr>
      <td align="center">
        <a href="https://github.com/Meikova/meikova-vision">
          <img src="./assets/icons/meikova-vision.png" width="56" height="56" alt="Meikova Vision" />
        </a>
      </td>
      <td>
        <a href="https://github.com/Meikova/meikova-vision"><strong>Meikova Vision</strong></a><br />
        <code>meikova-vision</code>
      </td>
      <td>
        <strong>Optical Wings RAW & HDR Imaging.</strong><br />
        Bộ xử lý ảnh chất lượng cao chuyên biệt cho file RAW, ghép phơi sáng đa khung (bracket merging), tone mapping thời gian thực và khử nhiễu ảnh số.
      </td>
      <td>Python, OpenCV, WebAssembly</td>
      <td align="center"><img src="https://img.shields.io/badge/Status-In%20Dev-A4DDFA?style=flat-square&labelColor=11151B" alt="In Dev" /></td>
    </tr>
    <tr>
      <td align="center">
        <a href="https://github.com/Meikova/meikova-flow">
          <img src="./assets/icons/meikova-flow.png" width="56" height="56" alt="Meikova Flow" />
        </a>
      </td>
      <td>
        <a href="https://github.com/Meikova/meikova-flow"><strong>Meikova Flow</strong></a><br />
        <code>meikova-flow</code>
      </td>
      <td>
        <strong>Slipstream ETL & Data Pipeline.</strong><br />
        Bộ máy xử lý, chuyển đổi và tích hợp dữ liệu tốc độ cao. Tự động hóa đồng bộ CSDL phân tán, lập lịch biểu ETL và xuất báo cáo phân tích tự động.
      </td>
      <td>Python, Pandas, SQLite, Worker Pool</td>
      <td align="center"><img src="https://img.shields.io/badge/Status-In%20Dev-FFD18F?style=flat-square&labelColor=11151B" alt="In Dev" /></td>
    </tr>
    <tr>
      <td align="center">
        <a href="https://github.com/Meikova/meikova-exchange">
          <img src="./assets/icons/meikova-exchange.png" width="56" height="56" alt="Meikova Exchange" />
        </a>
      </td>
      <td>
        <a href="https://github.com/Meikova/meikova-exchange"><strong>Meikova Exchange</strong></a><br />
        <code>meikova-exchange</code>
      </td>
      <td>
        <strong>Reciprocal Ribbons B2B Marketplace.</strong><br />
        Sàn giao dịch tài sản kỹ thuật số, dự án mã nguồn và giải pháp phần mềm doanh nghiệp với kiến trúc microservices và thanh toán ký quỹ (escrow).
      </td>
      <td>Node.js, TypeScript, Docker</td>
      <td align="center"><img src="https://img.shields.io/badge/Release-v1.0.0-F3C59D?style=flat-square&labelColor=11151B" alt="v1.0.0" /></td>
    </tr>
    <tr>
      <td align="center">
        <a href="https://github.com/Meikova/meikova-shield">
          <img src="./assets/icons/meikova-shield.png" width="56" height="56" alt="Meikova Shield" />
        </a>
      </td>
      <td>
        <a href="https://github.com/Meikova/meikova-shield"><strong>Meikova Shield</strong></a><br />
        <code>meikova-shield</code>
      </td>
      <td>
        <strong>Folded Bulwark Threat Sentinel.</strong><br />
        Hệ thống giám sát an ninh mạng, phát hiện nguy cơ web defacement và phân tích dấu hiệu tấn công thông qua mô hình học máy lai (hybrid ML).
      </td>
      <td>Python, Browser Shield, Threat Intel</td>
      <td align="center"><img src="https://img.shields.io/badge/Status-In%20Dev-92DDD4?style=flat-square&labelColor=11151B" alt="In Dev" /></td>
    </tr>
    <tr>
      <td align="center">
        <a href="https://github.com/Meikova/meikova-campus">
          <img src="./assets/icons/meikova-campus.png" width="56" height="56" alt="Meikova Campus" />
        </a>
      </td>
      <td>
        <a href="https://github.com/Meikova/meikova-campus"><strong>Meikova Campus</strong></a><br />
        <code>meikova-campus</code>
      </td>
      <td>
        <strong>Learning Commons & Course Hub.</strong><br />
        Nền tảng thương mại khóa học trực tuyến, hệ thống quản trị đào tạo (LMS), diễn đàn cộng đồng học viên và tích hợp lưu trữ đám mây.
      </td>
      <td>TypeScript, Express, Cloud Storage</td>
      <td align="center"><img src="https://img.shields.io/badge/Status-In%20Dev-C1B7F3?style=flat-square&labelColor=11151B" alt="In Dev" /></td>
    </tr>
    <tr>
      <td align="center">
        <a href="https://github.com/Meikova/meikova-traverse">
          <img src="./assets/icons/meikova-traverse.png" width="56" height="56" alt="Meikova Traverse" />
        </a>
      </td>
      <td>
        <a href="https://github.com/Meikova/meikova-traverse"><strong>Meikova Traverse</strong></a><br />
        <code>meikova-traverse</code>
      </td>
      <td>
        <strong>Navigable Chambers File Explorer.</strong><br />
        Trình duyệt và quản lý tệp tin đa nền tảng (Web & Desktop). Tích hợp giao thức SFTP, WebDAV, xem trước tập tin media và giải nén trực tuyến.
      </td>
      <td>TypeScript, Electron, Native FS</td>
      <td align="center"><img src="https://img.shields.io/badge/Status-In%20Dev-A8D5BF?style=flat-square&labelColor=11151B" alt="In Dev" /></td>
    </tr>
  </tbody>
</table>

---

## Lộ Trình Phát Triển Tương Lai (Upcoming Roadmap)

Bộ giải pháp quy hoạch theo 4 phân hệ chức năng chiến lược:

<table width="100%">
  <thead>
    <tr>
      <th width="25%">Bảo Mật & Trí Tuệ</th>
      <th width="25%">Sáng Tạo Đa Phương Tiện</th>
      <th width="25%">Hạ Tầng & Hệ Thống</th>
      <th width="25%">Cộng Tác & Quản Trị</th>
    </tr>
  </thead>
  <tbody>
    <tr valign="top">
      <td>
        <p>
          <img src="./assets/icons/meikova-agent.png" width="28" height="28" valign="middle" /> <strong>Agent</strong><br />
          <sub>Trợ lý AI tự trị hoạt động 100% cục bộ (Local LLM), điều phối quy trình an toàn không gửi dữ liệu ra ngoài.</sub>
        </p>
        <p>
          <img src="./assets/icons/meikova-vault.png" width="28" height="28" valign="middle" /> <strong>Vault</strong><br />
          <sub>Kho lưu trữ mã hóa dữ liệu bảo mật cấp độ quân sự, quản trị mật khẩu cá nhân Zero-Knowledge.</sub>
        </p>
      </td>
      <td>
        <p>
          <img src="./assets/icons/meikova-studio.png" width="28" height="28" valign="middle" /> <strong>Studio</strong><br />
          <sub>Biên tập âm thanh đa kênh chuyên nghiệp (DAW nhẹ), master track và thiết kế âm thanh không gian.</sub>
        </p>
        <p>
          <img src="./assets/icons/meikova-prism.png" width="28" height="28" valign="middle" /> <strong>Prism</strong><br />
          <sub>Cắt dựng và xử lý video tăng tốc phần cứng GPU, tối ưu biên tập và chuyển mã hàng loạt.</sub>
        </p>
        <p>
          <img src="./assets/icons/meikova-cast.png" width="28" height="28" valign="middle" /> <strong>Cast</strong><br />
          <sub>Truyền phát màn hình không dây, chia sẻ phiên làm việc trực tiếp thời gian thực WebRTC.</sub>
        </p>
      </td>
      <td>
        <p>
          <img src="./assets/icons/meikova-terminal.png" width="28" height="28" valign="middle" /> <strong>Terminal</strong><br />
          <sub>Mô phỏng terminal hiện đại, quản lý kết nối SSH đa máy chủ và điều phối cụm phân tán.</sub>
        </p>
        <p>
          <img src="./assets/icons/meikova-pulse.png" width="28" height="28" valign="middle" /> <strong>Pulse</strong><br />
          <sub>Bảng đo xa telemetry hệ thống, đo lường độ trễ mạng và cảnh báo bất thường thời gian thực.</sub>
        </p>
        <p>
          <img src="./assets/icons/meikova-sync.png" width="28" height="28" valign="middle" /> <strong>Sync</strong><br />
          <sub>Tiện ích đồng bộ dữ liệu ngang hàng (P2P), chia sẻ clipboard và truyền tập tin tốc độ mạng LAN.</sub>
        </p>
      </td>
      <td>
        <p>
          <img src="./assets/icons/meikova-doc.png" width="28" height="28" valign="middle" /> <strong>Doc</strong><br />
          <sub>Không gian ghi chép và quản trị tri thức dạng đồ thị, hỗ trợ định dạng Markdown mở cục bộ.</sub>
        </p>
        <p>
          <img src="./assets/icons/meikova-thread.png" width="28" height="28" valign="middle" /> <strong>Thread</strong><br />
          <sub>Hội thoại nhóm nội bộ và cộng tác phân tán với mã hóa đầu-cuối (E2EE) không qua máy chủ đám mây.</sub>
        </p>
        <p>
          <img src="./assets/icons/meikova-atlas.png" width="28" height="28" valign="middle" /> <strong>Atlas</strong><br />
          <sub>Công cụ hoạch định tiến độ phát triển dự án, theo dõi roadmap kỹ thuật và backlog liên repo.</sub>
        </p>
        <p>
          <img src="./assets/icons/meikova-dock.png" width="28" height="28" valign="middle" /> <strong>Dock</strong><br />
          <sub>Khay điều hướng ứng dụng và launcher tập trung, tích hợp phím tắt toàn cục và quản lý cửa sổ.</sub>
        </p>
        <p>
          <img src="./assets/icons/meikova-forge.png" width="28" height="28" valign="middle" /> <strong>Forge</strong><br />
          <sub>Bộ công cụ tự động hóa đóng gói đa nền tảng (Win/Mac/Linux/Android), ký số binary và xuất bản CI/CD.</sub>
        </p>
      </td>
    </tr>
  </tbody>
</table>

### Chi Tiết Danh Mục Quy Hoạch:

<table>
  <thead>
    <tr>
      <th width="70" align="center">Icon</th>
      <th width="180">Tên Dự Kiến</th>
      <th>Định Hướng Chức Năng</th>
      <th width="140">Mã Nhận Diện</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center"><img src="./assets/icons/meikova-agent.png" width="48" height="48" alt="Meikova Agent" /></td>
      <td><strong>Meikova Agent</strong></td>
      <td>Trợ lý AI tự trị hoạt động 100% cục bộ (Local LLM), điều phối tác vụ và tự động hóa quy trình không gửi dữ liệu ra ngoài.</td>
      <td><code>#C5A0FA</code> Cognitive link</td>
    </tr>
    <tr>
      <td align="center"><img src="./assets/icons/meikova-vault.png" width="48" height="48" alt="Meikova Vault" /></td>
      <td><strong>Meikova Vault</strong></td>
      <td>Kho lưu trữ dữ liệu mã hóa cấp độ quân sự, quản lý mật khẩu và chứng thư số cá nhân với kiến trúc Zero-Knowledge.</td>
      <td><code>#C7ADFF</code> Sealed chambers</td>
    </tr>
    <tr>
      <td align="center"><img src="./assets/icons/meikova-studio.png" width="48" height="48" alt="Meikova Studio" /></td>
      <td><strong>Meikova Studio</strong></td>
      <td>Phần mềm biên tập âm thanh đa kênh chuyên nghiệp (DAW nhẹ), master track và thiết kế âm thanh không gian.</td>
      <td><code>#F6A0D4</code> Spectral weave</td>
    </tr>
    <tr>
      <td align="center"><img src="./assets/icons/meikova-prism.png" width="48" height="48" alt="Meikova Prism" /></td>
      <td><strong>Meikova Prism</strong></td>
      <td>Phần mềm cắt dựng và biên tập video tăng tốc phần cứng GPU, tối ưu xuất bản nội dung nhanh và chuyển mã hàng loạt.</td>
      <td><code>#E9B0F1</code> Refracted splice</td>
    </tr>
    <tr>
      <td align="center"><img src="./assets/icons/meikova-cast.png" width="48" height="48" alt="Meikova Cast" /></td>
      <td><strong>Meikova Cast</strong></td>
      <td>Công cụ truyền phát màn hình, trình chiếu không dây và chia sẻ phiên làm việc trực tiếp thời gian thực qua WebRTC.</td>
      <td><code>#FFA991</code> Radiant fold</td>
    </tr>
    <tr>
      <td align="center"><img src="./assets/icons/meikova-terminal.png" width="48" height="48" alt="Meikova Terminal" /></td>
      <td><strong>Meikova Terminal</strong></td>
      <td>Trình mô phỏng terminal hiện đại, quản lý kết nối SSH đa máy chủ, điều phối container và giám sát cụm phân tán.</td>
      <td><code>#D3EE88</code> Command lattice</td>
    </tr>
    <tr>
      <td align="center"><img src="./assets/icons/meikova-pulse.png" width="48" height="48" alt="Meikova Pulse" /></td>
      <td><strong>Meikova Pulse</strong></td>
      <td>Bảng điều khiển giám sát sức khỏe hệ thống, đo lường độ trễ mạng, mức sử dụng tài nguyên và gửi cảnh báo thời gian thực.</td>
      <td><code>#F5A7BE</code> Telemetry crest</td>
    </tr>
    <tr>
      <td align="center"><img src="./assets/icons/meikova-sync.png" width="48" height="48" alt="Meikova Sync" /></td>
      <td><strong>Meikova Sync</strong></td>
      <td>Tiện ích đồng bộ dữ liệu ngang hàng (P2P), truyền tập tin tốc độ LAN/Mesh và đồng bộ clipboard giữa máy tính và điện thoại.</td>
      <td><code>#A7BBFF</code> Reciprocal orbit</td>
    </tr>
    <tr>
      <td align="center"><img src="./assets/icons/meikova-doc.png" width="48" height="48" alt="Meikova Doc" /></td>
      <td><strong>Meikova Doc</strong></td>
      <td>Không gian ghi chép và quản trị tri thức dạng đồ thị, hỗ trợ định dạng Markdown mở và lưu trữ cục bộ vĩnh viễn.</td>
      <td><code>#91DAC0</code> Continuity folio</td>
    </tr>
    <tr>
      <td align="center"><img src="./assets/icons/meikova-thread.png" width="48" height="48" alt="Meikova Thread" /></td>
      <td><strong>Meikova Thread</strong></td>
      <td>Ứng dụng trò chuyện nhóm và cộng tác nội bộ với mã hóa đầu-cuối (E2EE), loại bỏ trung gian máy chủ đám mây.</td>
      <td><code>#8CD6ED</code> Conversation knot</td>
    </tr>
    <tr>
      <td align="center"><img src="./assets/icons/meikova-atlas.png" width="48" height="48" alt="Meikova Atlas" /></td>
      <td><strong>Meikova Atlas</strong></td>
      <td>Công cụ lập kế hoạch phát triển dự án, theo dõi roadmap kỹ thuật, quản lý backlog và liên kết chéo các repository.</td>
      <td><code>#B8D995</code> Terrace link</td>
    </tr>
    <tr>
      <td align="center"><img src="./assets/icons/meikova-dock.png" width="48" height="48" alt="Meikova Dock" /></td>
      <td><strong>Meikova Dock</strong></td>
      <td>Khay điều hướng ứng dụng và bố trí không gian làm việc tập trung, tích hợp phím tắt toàn cục và quản lý cửa sổ thông minh.</td>
      <td><code>#E5D38E</code> Workspace cradle</td>
    </tr>
    <tr>
      <td align="center"><img src="./assets/icons/meikova-forge.png" width="48" height="48" alt="Meikova Forge" /></td>
      <td><strong>Meikova Forge</strong></td>
      <td>Bộ công cụ tự động hóa đóng gói ứng dụng đa nền tảng (Win/Mac/Linux/Android), ký số binary và xuất bản phát hành CI/CD.</td>
      <td><code>#F7AE7F</code> Forged continuum</td>
    </tr>
  </tbody>
</table>

---

## Chuẩn Mực Thiết Kế: Ambient Instrument

Toàn bộ ứng dụng trong hệ sinh thái tuân thủ nghiêm ngặt ngôn ngữ thiết kế **Ambient Instrument**:

- **Không gian màu OKLCH:** Chuyển đổi ánh sáng mượt mà với CSS `@property`, thích ứng độ tương phản chuẩn xác cho chế độ nền tối (Dark-first).
- **Hệ thống phông chữ 3 tầng:**
  - Tiêu đề & Nhận diện: **Unbounded**
  - Giao diện & Thao tác: **Be Vietnam Pro** (tối ưu 100% dấu thanh tiếng Việt)
  - Số liệu & Đo xa kỹ thuật: **JetBrains Mono**
- **100% Vector SVG:** Không dùng font icon bên ngoài; mọi biểu tượng là vector nội tuyến có tâm quang học chuẩn xác.
- **Tối giản phụ thuộc:** Ưu tiên mã nguồn JavaScript thuần (Vanilla JS / ES Modules), loại bỏ framework cồng kềnh, tối đa tốc độ kết xuất và tiết kiệm RAM/CPU.

---

## Đóng Góp & Hợp Tác

Hệ sinh thái Meikova hoan nghênh mọi đóng góp từ cộng đồng:
- Báo cáo lỗi kỹ thuật & Đề xuất tính năng mới qua **Issues** tại từng repository.
- Tham gia thảo luận kiến trúc tại **Discussions**.
- Tuân thủ quy chuẩn bảo vệ quyền riêng tư, an toàn dữ liệu và kiến trúc Offline-First khi gửi **Pull Request**.

<div align="center">

---

<sub>© 2026 Meikova Ecosystem. Giấy phép mã nguồn mở MIT. Phát triển vì một môi trường phần mềm tự do, riêng tư và bền vững.</sub>

</div>
