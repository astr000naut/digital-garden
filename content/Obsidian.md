
# 🗺️ OBSIDIAN CHEAT SHEET

## 1. 🏗️ Khái Niệm

| Thuật ngữ | Giải thích đơn giản |
| :--- | :--- |
| **Vault** | Là cái "két sắt" (Folder) chứa toàn bộ dữ liệu của bạn. Nó nằm trên máy tính, không phải trên mây. |
| **Note** | Là một trang ghi chú, một file văn bản (`.md`). |
| **Markdown** | Ngôn ngữ quy định cách trình bày văn bản (tô đậm, nghiêng...) bằng các ký tự đặc biệt. |
| **Plugin** | Tính năng cài thêm để Obsidian mạnh hơn (như cài App trên điện thoại). |

---

## 2. ✍️ Cú Pháp Markdown (Định Dạng Văn Bản)
*Gõ ký tự bên trái để hiển thị kết quả bên phải.*

| Chức năng | Bạn gõ (Input) | Hiển thị (Output) |
| :--- | :--- | :--- |
| **Tiêu đề** | `# H1`, `## H2`, `### H3` | **Tiêu đề lớn**, **nhỏ hơn**... |
| **In đậm** | `**Nội dung**` | **Nội dung** |
| **In nghiêng** | `*Nội dung*` | *Nội dung* |
| **Gạch chân** | `==Nội dung==` | ==Nội dung== (Highlight) |
| **Gạch ngang** | `~~Nội dung~~` | ~~Nội dung~~ (Đã xóa) |
| **Danh sách** | `- Nội dung` hoặc `1. Nội dung` | • Nội dung / 1. Nội dung |
| **Việc cần làm**| `- [ ] Mua sữa` | ⬜ Mua sữa |
| **Trích dẫn** | `> Câu nói hay` | <blockquote>Câu nói hay</blockquote> |
| **Code/Lệnh** | Dùng dấu huyền \`Code\` | `Code` |
| **Kẻ ngang** | `---` | (Đường kẻ ngang phân cách) |

---

## 3. 🔗 Kết Nối & Mở Rộng (Sức Mạnh Thật Sự)

Đây là phần quan trọng nhất biến Obsidian thành "Bộ não thứ hai".

### A. Liên kết (Linking)
*   **Liên kết nội bộ:** Gõ `[[Tên bài viết]]`.
    *   *Tác dụng:* Bấm vào để nhảy sang bài viết đó.
*   **Nhúng nội dung (Embed):** Gõ `![[Tên bài viết]]`.
    *   *Tác dụng:* Hiển thị luôn nội dung bài kia vào bài này mà không cần bấm chuyển trang.
*   **Liên kết ngoài:** Gõ `[Tên hiển thị](Link web)`.
    *   *Ví dụ:* `[Google](https://google.com)`

### B. Phân loại
*   **Tags (Thẻ):** Gõ `#từ-khóa` (Ví dụ: `#thói-quen`, `#sách-hay`).
    *   *Lưu ý:* Không dùng khoảng trắng trong tag.
*   **Folder:** Kéo thả file vào thư mục như Windows/Mac bình thường.

### C. Chèn ảnh & File
*   **Cách nhanh nhất:** Copy ảnh/file và Paste thẳng vào ghi chú (`Ctrl + V`).
*   **Thủ công:** Gõ `![[Tên ảnh.png]]`.

---

## 4. 🎹 Phím Tắt "Thần Thánh" (Hotkeys)
*Đừng dùng chuột, hãy dùng phím để thao tác nhanh gấp 3 lần.*

| Phím tắt (Win / Mac) | Chức năng (Học thuộc lòng nhé!) |
| :--- | :--- |
| `Ctrl + P` / `Cmd + P` | **Command Palette:** Mở thanh lệnh để làm MỌI THỨ (đổi màu, xuất file, v.v.). |
| `Ctrl + O` / `Cmd + O` | **Quick Switcher:** Tìm và mở nhanh một ghi chú. |
| `Ctrl + N` / `Cmd + N` | **New Note:** Tạo ghi chú mới ngay lập tức. |
| `Ctrl + E` / `Cmd + E` | Chuyển đổi chế độ **Xem** (Preview) và **Sửa** (Edit). |
| `Ctrl + F` / `Cmd + F` | Tìm kiếm chữ trong bài viết hiện tại. |
| `Ctrl + Shift + F` | Tìm kiếm trong **toàn bộ** Vault. |

---

## 5. 🎨 Trang Trí & Nâng Cao (Callouts)

Obsidian hỗ trợ các khung thông báo đẹp mắt (Callouts).

**Cú pháp:**
```

> [!NOTE] Tiêu đề  
> Nội dung ghi chú ở đây.

```

**Các loại Callout phổ biến:** (Thay chữ `NOTE` bằng các từ sau)
*   `[!TIP]` 💡 Mẹo hay
*   `[!WARNING]` ⚠️ Cảnh báo
*   `[!DANGER]` 🛑 Nguy hiểm
*   `[!QUESTION]` ❓ Câu hỏi
*   `[!SUCCESS]` ✅ Thành công

---

## 6. 🛠️ Quy Trình 3 Bước Cho Người Mới

1.  **Capture (Ghi lại):** Đừng lo về cấu trúc. Mở máy lên, bấm `Ctrl + N`, viết ngay ý tưởng xuống. Dùng `#tag` để đánh dấu chủ đề.
2.  **Organize (Sắp xếp):** Cuối ngày/tuần, đọc lại. Dùng `[[Link]]` để nối ý tưởng này với ý tưởng khác có liên quan.
3.  **Distill (Chắt lọc):** Từ những liên kết đó, tổng hợp lại thành kiến thức của riêng mình (Graph View sẽ giúp bạn nhìn thấy bức tranh toàn cảnh).
