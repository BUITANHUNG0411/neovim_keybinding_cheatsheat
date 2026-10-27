# NeoVim Beginner Cheat Sheet 🚀

Welcome to my personal cheat sheet for basic NeoVim shortcuts! This covers navigation, editing, visual selection, file management, and window splitting.

---

## 1. Basic Editing & History
| Shortcut | Description |
| :--- | :--- |
| `u` | Undo (Hoàn tác) |
| `Ctrl + r` | Redo (Làm lại) |
| `o` | Mở dòng mới phía dưới và chuyển sang chế độ edit |
| `Shift + o` | Mở dòng mới phía trên và chuyển sang chế độ edit |
| `d` | Cut (Xóa/Cắt văn bản) |
| `Y` | Copy (`Shift + v` rồi `Y` để copy nguyên dòng) |
| `p` | Paste (Dán phía sau/dưới) |
| `Shift + p` | Paste dòng trước/trên |

---

## 2. Navigation & Motion
| Shortcut | Description |
| :--- | :--- |
| `w` | Di chuyển tới từ tiếp theo |
| `b` | Di chuyển tới từ trước |
| `0` | Về đầu dòng |
| `$` (`Shift + 4`) | Về cuối dòng |
| `gg` | Di chuyển về dòng đầu tiên của file |
| `G` | Di chuyển về dòng cuối cùng của file |
| `:[số dòng]` | Di chuyển con trỏ tới một dòng cụ thể |

---

## 3. Visual Mode (Bôi đen & Chọn vùng)
| Shortcut | Description |
| :--- | :--- |
| `v` | Visual mode (bôi đen tự do theo con trỏ) |
| `Shift + v` | Visual line (bôi đen theo từng dòng) |
| `viw` | Visual in word (chọn nhanh 1 từ hiện tại) |
| `ggVG` | Chọn toàn bộ nội dung file |

---

## 4. Search & Replace
| Shortcut | Description |
| :--- | :--- |
| `/ + [từ]` | Tìm kiếm từ trong file |
| `Shift + 8` (`*`) | Tìm các từ giống với từ đang đứng |
| `n` | Đi tìm kết quả giống tiếp theo |
| `Shift + n` | Đi tìm kết quả giống trước đó |
| `:%s/[từ cũ]/[từ mới]` | Thay thế từ (Search & Replace) |

---

## 5. File & Window Management
| Shortcut | Description |
| :--- | :--- |
| `:e [tên file]` | Mở file |
| `:w` | Lưu file (Save) |
| `:wq` | Lưu và thoát (Save and Quit) |
| `:bq` | Đóng buffer hiện tại (đóng file đang mở) |
| `:vs [tên file]` | Chia đôi màn hình theo chiều dọc (Vertical split) |
| `Ctrl + w` (thả ra) + Mũi tên | Di chuyển qua lại giữa các cửa sổ |
| `Ctrl + w` (giữ) + Mũi tên | Thay đổi kích thước cửa sổ |
| `Ctrl + w` + `Shift + J/K/L/H` | Thay đổi vị trí các cửa sổ |