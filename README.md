<div align="center">

<img src="./assets/icons/meikova.png" width="96" height="96" alt="Meikova Logo" />

# MEIKOVA

**Build what matters.**  
*Hệ sinh thái phần mềm mã nguồn mở đa nền tảng, thiết kế Ambient Dark và kiến trúc Offline-First.*

<p align="center">
  <img src="https://img.shields.io/badge/License-MIT-9EF6D0?style=flat-square&labelColor=11151B" alt="License MIT" />
  <img src="https://img.shields.io/badge/Architecture-Offline--First-83E8AC?style=flat-square&labelColor=11151B" alt="Offline-First" />
  <img src="https://img.shields.io/badge/Auth-Ed25519%20SSO-A6C5FF?style=flat-square&labelColor=11151B" alt="Ed25519 SSO" />
  <img src="https://img.shields.io/badge/Design-Ambient%20Instrument-FFB38A?style=flat-square&labelColor=11151B" alt="Ambient Instrument" />
  <img src="https://img.shields.io/badge/Telemetry-Zero%20Tracking-92DDD4?style=flat-square&labelColor=11151B" alt="Zero Tracking" />
</p>

---

</div>

## Triết Lý Phát Triển & Giá Trị Cốt Lõi

Meikova hướng tới các giải pháp phần mềm độc lập, đề cao quyền riêng tư và hiệu năng thực tế cho người dùng:

- **Mã nguồn mở & Tự do dữ liệu:** 100% minh bạch với giấy phép MIT, loại bỏ hoàn toàn mã theo dõi người dùng (zero tracking), hỗ trợ tự lưu trữ (self-hostable) và toàn quyền kiểm soát dữ liệu.
- **Tiện ích đa nền tảng:** Phục vụ trực tiếp công việc hàng ngày trên Windows, macOS, Linux, Android, iOS, Web PWA và Browser Extensions.
- **Hiệu năng & Offline-First:** Dữ liệu ưu tiên lưu trữ cục bộ qua SQLite WAL / Turso LibSQL Cloud, thời gian phản hồi tiệm cận 0ms, hoạt động ổn định ngay cả khi mất kết nối mạng.

---

## Bảng Nhận Diện 26 Thương Hiệu (Folded Continuum)

Toàn bộ hệ sinh thái tuân thủ ngôn ngữ hình học **Folded Continuum** – phát triển từ cấu trúc hai thùy và giao điểm lemniscate không lặp lại:

<div align="center">
  <img src="./assets/meikova-identity-board.png" width="100%" alt="Meikova 26 Marks - One Continuum Identity Board" />
</div>

---

## 4 Trụ Cột Nền Tảng Cốt Lõi (Core Ecosystem)

Bốn giải pháp hạ tầng định hình năng lực vận hành của hệ sinh thái Meikova:

<table width="100%">
  <thead>
    <tr>
      <th width="70" align="center">Icon</th>
      <th width="200">Dự Án</th>
      <th>Mô Tả Kỹ Thuật</th>
      <th width="160">Nền Tảng</th>
      <th width="130" align="center">Trạng Thái</th>
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
        <strong>Identity Gateway & Universal SSO.</strong><br />
        Cổng xác thực tập trung, xác minh token Ed25519 offline (~0.1ms), PBKDF2/scrypt, Google OAuth 2.0 GIS, tích hợp Turso LibSQL Cloud.
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
        Điều khiển máy trạm từ xa và truyền dữ liệu đo xa (telemetry) độ trễ siêu thấp qua WebSocket. Web client truy cập trực tiếp không cần cài đặt.
      </td>
      <td>Desktop (Win/Mac/Linux), Web PWA</td>
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
        Bộ máy mashup âm thanh thời gian thực, tách 4 stem Demucs (Vocals/Drums/Bass/Other), hiệu ứng DSP và soundscape player với Canvas visualizer.
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
        Thu nhận và trích xuất đa phương tiện hiệu năng cao. Hỗ trợ tải đa luồng, pipeline FFmpeg, stream capture và vượt chặn kiểm duyệt qua Google DoH.
      </td>
      <td>Desktop Shell, Web, Chrome Extension</td>
      <td align="center"><img src="https://img.shields.io/badge/Release-v2.0.7-83C4FF?style=flat-square&labelColor=11151B" alt="v2.0.7" /></td>
    </tr>
  </tbody>
</table>

---

## Dự Án Ứng Dụng Đang Phát Triển (Domain Extensions)

Bộ công cụ chuyên biệt phục vụ các tác vụ công việc kỹ thuật, quản trị dữ liệu và đời sống:

<table width="100%">
  <thead>
    <tr>
      <th width="70" align="center">Icon</th>
      <th width="200">Dự Án</th>
      <th>Nghiệp Vụ & Nền Tảng Kỹ Thuật</th>
      <th width="160">Stack Chính</th>
      <th width="130" align="center">Trạng Thái</th>
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
        Quản lý tài chính cá nhân, bóc tách hóa đơn tự động qua AI cục bộ, theo dõi thu chi đa tiền tệ và phân tích ngân sách.
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
        Xử lý ảnh RAW chất lượng cao, ghép phơi sáng đa khung (bracket merging) và tone mapping thời gian thực.
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
        Trích xuất, chuyển đổi và tích hợp dữ liệu tốc độ cao. Tự động hóa đồng bộ CSDL phân tán và xuất báo cáo biểu mẫu.
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
        Sàn giao dịch tài sản kỹ thuật số, dự án mã nguồn và giải pháp phần mềm doanh nghiệp với thanh toán ký quỹ (escrow).
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
        Giám sát an ninh mạng, phát hiện web defacement và phân tích dấu hiệu tấn công qua mô hình học máy lai (hybrid ML).
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
        Nền tảng thương mại khóa học trực tuyến, quản trị đào tạo (LMS), diễn đàn trao đổi và đồng bộ lưu trữ đám mây.
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
        Trình duyệt và quản lý tập tin đa nền tảng (Web & Desktop). Tích hợp giao thức SFTP, WebDAV và xem trước đa phương tiện.
      </td>
      <td>TypeScript, Electron, Native FS</td>
      <td align="center"><img src="https://img.shields.io/badge/Status-In%20Dev-A8D5BF?style=flat-square&labelColor=11151B" alt="In Dev" /></td>
    </tr>
  </tbody>
</table>

---

## Lộ Trình Phát Triển Tương Lai (Upcoming Roadmap)

Danh mục 13 giải pháp quy hoạch theo 4 phân hệ chiến lược:

<table width="100%">
  <thead>
    <tr>
      <th width="70" align="center">Icon</th>
      <th width="180">Dự Án</th>
      <th width="190">Phân Hệ</th>
      <th>Định Hướng Chức Năng</th>
      <th width="150" align="center">Mã Nhận Diện</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center"><img src="./assets/icons/meikova-agent.png" width="48" height="48" alt="Meikova Agent" /></td>
      <td><strong>Meikova Agent</strong></td>
      <td>Bảo Mật & Trí Tuệ</td>
      <td>Trợ lý AI tự trị hoạt động 100% cục bộ (Local LLM), điều phối quy trình và tự động hóa tác vụ không gửi dữ liệu ra ngoài.</td>
      <td align="center"><code>#C5A0FA</code><br /><sub>Cognitive link</sub></td>
    </tr>
    <tr>
      <td align="center"><img src="./assets/icons/meikova-vault.png" width="48" height="48" alt="Meikova Vault" /></td>
      <td><strong>Meikova Vault</strong></td>
      <td>Bảo Mật & Trí Tuệ</td>
      <td>Kho lưu trữ mã hóa dữ liệu cấp độ quân sự, quản trị mật khẩu cá nhân và chứng thư số theo chuẩn Zero-Knowledge.</td>
      <td align="center"><code>#C7ADFF</code><br /><sub>Sealed chambers</sub></td>
    </tr>
    <tr>
      <td align="center"><img src="./assets/icons/meikova-studio.png" width="48" height="48" alt="Meikova Studio" /></td>
      <td><strong>Meikova Studio</strong></td>
      <td>Sáng Tạo Đa Phương Tiện</td>
      <td>Phần mềm biên tập âm thanh đa kênh chuyên nghiệp (DAW nhẹ), xử lý master track và thiết kế âm thanh không gian.</td>
      <td align="center"><code>#F6A0D4</code><br /><sub>Spectral weave</sub></td>
    </tr>
    <tr>
      <td align="center"><img src="./assets/icons/meikova-prism.png" width="48" height="48" alt="Meikova Prism" /></td>
      <td><strong>Meikova Prism</strong></td>
      <td>Sáng Tạo Đa Phương Tiện</td>
      <td>Phần mềm cắt dựng và xử lý video tăng tốc phần cứng GPU, tối ưu xuất bản nội dung nhanh và chuyển mã hàng loạt.</td>
      <td align="center"><code>#E9B0F1</code><br /><sub>Refracted splice</sub></td>
    </tr>
    <tr>
      <td align="center"><img src="./assets/icons/meikova-cast.png" width="48" height="48" alt="Meikova Cast" /></td>
      <td><strong>Meikova Cast</strong></td>
      <td>Sáng Tạo Đa Phương Tiện</td>
      <td>Công cụ truyền phát màn hình không dây, chia sẻ phiên làm việc trực tiếp thời gian thực qua giao thức WebRTC.</td>
      <td align="center"><code>#FFA991</code><br /><sub>Radiant fold</sub></td>
    </tr>
    <tr>
      <td align="center"><img src="./assets/icons/meikova-terminal.png" width="48" height="48" alt="Meikova Terminal" /></td>
      <td><strong>Meikova Terminal</strong></td>
      <td>Hạ Tầng & Hệ Thống</td>
      <td>Trình mô phỏng terminal hiện đại, quản lý phiên SSH đa máy chủ, điều phối container và giám sát cụm phân tán.</td>
      <td align="center"><code>#D3EE88</code><br /><sub>Command lattice</sub></td>
    </tr>
    <tr>
      <td align="center"><img src="./assets/icons/meikova-pulse.png" width="48" height="48" alt="Meikova Pulse" /></td>
      <td><strong>Meikova Pulse</strong></td>
      <td>Hạ Tầng & Hệ Thống</td>
      <td>Bảng điều khiển đo xa telemetry hệ thống, giám sát độ trễ mạng, tài nguyên phần cứng và cảnh báo thời gian thực.</td>
      <td align="center"><code>#F5A7BE</code><br /><sub>Telemetry crest</sub></td>
    </tr>
    <tr>
      <td align="center"><img src="./assets/icons/meikova-sync.png" width="48" height="48" alt="Meikova Sync" /></td>
      <td><strong>Meikova Sync</strong></td>
      <td>Hạ Tầng & Hệ Thống</td>
      <td>Tiện ích đồng bộ dữ liệu ngang hàng (P2P), truyền tập tin tốc độ mạng nội bộ và đồng bộ clipboard đa thiết bị.</td>
      <td align="center"><code>#A7BBFF</code><br /><sub>Reciprocal orbit</sub></td>
    </tr>
    <tr>
      <td align="center"><img src="./assets/icons/meikova-doc.png" width="48" height="48" alt="Meikova Doc" /></td>
      <td><strong>Meikova Doc</strong></td>
      <td>Cộng Tác & Quản Trị</td>
      <td>Không gian ghi chép và quản trị tri thức dạng đồ thị, hỗ trợ định dạng Markdown mở và lưu trữ cục bộ vĩnh viễn.</td>
      <td align="center"><code>#91DAC0</code><br /><sub>Continuity folio</sub></td>
    </tr>
    <tr>
      <td align="center"><img src="./assets/icons/meikova-thread.png" width="48" height="48" alt="Meikova Thread" /></td>
      <td><strong>Meikova Thread</strong></td>
      <td>Cộng Tác & Quản Trị</td>
      <td>Ứng dụng trò chuyện nhóm và cộng tác phân tán với mã hóa đầu-cuối (E2EE), loại bỏ trung gian máy chủ đám mây.</td>
      <td align="center"><code>#8CD6ED</code><br /><sub>Conversation knot</sub></td>
    </tr>
    <tr>
      <td align="center"><img src="./assets/icons/meikova-atlas.png" width="48" height="48" alt="Meikova Atlas" /></td>
      <td><strong>Meikova Atlas</strong></td>
      <td>Cộng Tác & Quản Trị</td>
      <td>Công cụ lập kế hoạch phát triển dự án, theo dõi roadmap kỹ thuật, quản lý backlog và liên kết chéo repository.</td>
      <td align="center"><code>#B8D995</code><br /><sub>Terrace link</sub></td>
    </tr>
    <tr>
      <td align="center"><img src="./assets/icons/meikova-dock.png" width="48" height="48" alt="Meikova Dock" /></td>
      <td><strong>Meikova Dock</strong></td>
      <td>Cộng Tác & Quản Trị</td>
      <td>Khay điều hướng ứng dụng và launcher tập trung, tích hợp phím tắt toàn cục và quản lý không gian làm việc.</td>
      <td align="center"><code>#E5D38E</code><br /><sub>Workspace cradle</sub></td>
    </tr>
    <tr>
      <td align="center"><img src="./assets/icons/meikova-forge.png" width="48" height="48" alt="Meikova Forge" /></td>
      <td><strong>Meikova Forge</strong></td>
      <td>Cộng Tác & Quản Trị</td>
      <td>Bộ công cụ tự động hóa đóng gói ứng dụng đa nền tảng (Win/Mac/Linux/Android), ký số binary và xuất bản phát hành CI/CD.</td>
      <td align="center"><code>#F7AE7F</code><br /><sub>Forged continuum</sub></td>
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
