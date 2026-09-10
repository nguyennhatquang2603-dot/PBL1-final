# PBL1 Final — My Sorting Game

Trò chơi minh hoạ các thuật toán sắp xếp, viết bằng **C++** với thư viện đồ hoạ **SFML 3**.
Đây là bản build cho môn PBL1.

## Chạy game

> Chỉ chạy trên **Windows (x64)**.

1. Tải/clone repo về.
2. Vào thư mục `MySortingGame/`.
3. Chạy `ConsoleApplication1.exe`.

Các file `sfml-*-3.dll` đã đi kèm nên không cần cài SFML riêng.
Nếu Windows báo thiếu Visual C++ Runtime, cài
[Microsoft Visual C++ Redistributable (x64)](https://aka.ms/vs/17/release/vc_redist.x64.exe).

## Cấu trúc thư mục

```
MySortingGame/
├── ConsoleApplication1.exe   # file thực thi
├── sfml-*-3.dll              # thư viện SFML 3 (runtime)
├── png/                      # hình ảnh giao diện
├── sound/                    # hiệu ứng âm thanh (.wav)
├── Pridi/                    # font Pridi (SIL Open Font License)
└── arial/                    # ARIAL.TTF, ARIALBD.TTF
```

Game nạp tài nguyên theo **đường dẫn tương đối** (`png/...`, `sound/...`,
`arial/...`, `pridi/...`), vì vậy phải chạy exe khi thư mục hiện hành là
`MySortingGame/`.

## Ghi chú về font

- **Pridi** — kèm theo giấy phép `Pridi/OFL.txt` (SIL OFL 1.1), được phép phân phối.
- **Arial** (`arial/ARIAL.TTF`, `arial/ARIALBD.TTF`) — font bản quyền của
  Microsoft/Monotype, chỉ để trong repo cho game chạy được ngay. Nếu bạn fork
  và phát hành lại, hãy thay bằng font tự do (ví dụ
  [Liberation Sans](https://github.com/liberationfonts/liberation-fonts) hoặc
  [DejaVu Sans](https://dejavu-fonts.github.io/)) và đổi tên tương ứng.

## Mã nguồn

Repo này hiện chỉ chứa **bản build + tài nguyên**, chưa có mã nguồn C++
(`.cpp/.h`) và file project Visual Studio. Bổ sung sau nếu cần nộp kèm source.
