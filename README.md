# vket-winter2026

Vket 2026 Winter のブースが読み込む画像の置き場です。

## どの入稿物がどのファイルを読むか

ブースが読む画像の名前は「枠の並びを決めた日」で付けます。中身の差し替えは同じファイルを上書きし、枠の並びが変わった時（入稿し直す時）だけ新しい名前を作ります。古い入稿物が読むファイルは変えず、消しません。

| ファイル | 読む入稿物 | 枠の並び |
|:--|:--|:--|
| `booth.png` | 10-23 までの入稿物 | ポスターと札 48 枠（屋根裏の板 32 枚）・ショーケースの 3D の形 8 枠 |
| `booth_20261024.png` | 10-24 の並びの入稿物 | 屋根裏の板を 16 枚に減らした並び・表の看板 5 枚（枠 48〜52）・ショーケースの 3D の形 8 枠 |

## 中身

- `booth.png`: ブースのポスター・商品の札・屋根裏の展示の絵（2048×2048 の RGBA）。絵を BC1 の形に詰めてあり、ブースのシェーダーが解いて映します（普通の画像としては見られません）
  - ショーケースの 3D の形（8 枠）も同じ 1 枚に詰めてあります。今は仮の形です（1 枠目は空・ほかは絵になるカメラと試しの球・スザンヌ（Blender）・写真は下の CC0 の Mountain and Landscape.jpg と Sunset at Sea MET DT235919.jpg）
  - 今は仮の絵です（番号と「差し替えできる仮の絵」の帯つき）
  - 仮の写真は Wikimedia Commons の CC0 の物です: Mountain and Landscape.jpg・Red maple flowers with a bee.jpg・Beech and ferns in Gullmarsskogen.jpg・Chateau Frontenac illuminated at night in Quebec City.jpg・Foodiesfeed.com pouring-honey-on-pancakes-with-walnuts.jpg・Sunset at Sea MET DT235919.jpg・Autumn leaves on the ground in Quebec City.jpg・Domestic shorthair cat portrait in grass.jpg
- `booth_20261024.png`: 形式は `booth.png` と同じ（2048×2048 の RGBA・BC1 と 3D の形を詰めた物）
  - ポスターと札は `booth.png` の残す枠と同じ絵です（上の CC0 の写真を含みます）。屋根裏の減らした 16 枠は空です
  - 表の看板 5 枚（枠 48〜52）は番号入りの仮の絵です
  - ショーケースの 3D の形 8 枠は仮置きです（1 枠目は絵になるカメラ・2〜8 枠目はこのブースの家具のミニチュア）
- `alpha_probe.png`: 試しの画像（落とした画像のアルファが値のまま届くかを確かめた・ブースは読まない）
- `booth_model_test.png`: 試しの画像（ブースは読まない）。屋根裏のポスターを半分（16 枚）にした配置のポスターに、ショーケースの 3D の形を 8 枠ぶん足した物。形は絵になるカメラと試しの球・スザンヌ（Blender）で、写真は上と同じ CC0 の Mountain and Landscape.jpg と Sunset at Sea MET DT235919.jpg
