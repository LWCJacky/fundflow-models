# fundflow-models

經辦 Flow（fundflow）工具模組在瀏覽器端去背所用的模型檔，經 jsDelivr 提供：

- `u2netp.onnx`（4.4MB）：U²-Net 輕量版，輸入 320×320，輸出單通道遮罩。
  - 授權：Apache-2.0（U-2-Net，Xuebin Qin et al.，https://github.com/xuebinqin/U-2-Net）
  - 來源：rembg 的 release 資產 https://github.com/danielgatis/rembg/releases/download/v0.0.0/u2netp.onnx
  - SHA-256：見 `u2netp.onnx.sha256`

載入網址（鎖 tag，jsDelivr 永久快取）：
`https://cdn.jsdelivr.net/gh/LWCJacky/fundflow-models@v1/u2netp.onnx`
