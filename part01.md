# さまざまなマテリアルクラス
## MeshBasicMaterial
THREE.MeshBasicMaterialクラスはライティングを考慮しないマテリアルです。  ::陰がつかないので均一な塗りつぶした状態**になります。開発中にライティングを無視して、動作確認するときに役立つでしょう。


大体がTextureの設定（map）。aoのオブジェクトはambient oclusion map のこと。
### ambient occlusion
シーン内の環境光（ambient）がどの程度さえぎられている（occlusion）かを計算するレンダリング方法のこと。シーン内の1点から半球方向に対する光の遮蔽（しゃへい）状況を計算し、リアルな影を生成する。比較的少ない計算量で、柔らかな陰影を表現できる。特に明るい色のモデルの陰影を表現するのに有効である。

[https://threejs.org/docs/#api/en/materials/MeshBasicMaterial](https://threejs.org/docs/#api/en/materials/MeshBasicMaterial)

## MeshBasicMaterial
THREE.MeshNormalMaterialクラスはノーマルのカラーをRGBで可視化するマテリアルです。ライティングを必要としないため、手軽に動作確認するときに役立つでしょう。

[https://threejs.org/docs/#api/en/materials/MeshNormalMaterial](https://threejs.org/docs/#api/en/materials/MeshNormalMaterial)