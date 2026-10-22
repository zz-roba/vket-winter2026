# vket-winter2026

Vket 2026 Winter のブースが読み込む画像の置き場です。

- `booth.png`: ブースのポスター・商品の札・屋根裏の展示の絵（2048×2048 の RGBA）。絵を BC1 の形に詰めてあり、ブースのシェーダーが解いて映します（普通の画像としては見られません）
  - ショーケースの 3D の形（8 枠）も同じ 1 枚に詰めてあります。今は仮の形です（1 枠目は空・ほかは絵になるカメラと試しの球・スザンヌ（Blender）・写真は下の CC0 の Mountain and Landscape.jpg と Sunset at Sea MET DT235919.jpg）
  - 今は仮の絵です（番号と「差し替えできる仮の絵」の帯つき）
  - 仮の写真は Wikimedia Commons の CC0 の物です: Mountain and Landscape.jpg・Red maple flowers with a bee.jpg・Beech and ferns in Gullmarsskogen.jpg・Chateau Frontenac illuminated at night in Quebec City.jpg・Foodiesfeed.com pouring-honey-on-pancakes-with-walnuts.jpg・Sunset at Sea MET DT235919.jpg・Autumn leaves on the ground in Quebec City.jpg・Domestic shorthair cat portrait in grass.jpg
- `alpha_probe.png`: 試しの画像（落とした画像のアルファが値のまま届くかを確かめた・ブースは読まない）
- `booth_model_test.png`: 試しの画像（ブースはまだ読まない）。屋根裏のポスターを半分（16 枚）にした配置のポスターに、ショーケースの 3D の形を 8 枠ぶん足した物。形は絵になるカメラと試しの球・スザンヌ（Blender）で、写真は上と同じ CC0 の Mountain and Landscape.jpg と Sunset at Sea MET DT235919.jpg
