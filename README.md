1.11.2024 :
- Polygon annotation
- 1 photo 1 object
- just yolov8 (small ver)
- 98.88% acc
- tapi deteksi betumpuk antara mi aceh & spageti wow
- 500 ms inference

2.11.2024 :
- Pure bounding box
- 1 photo 1 object
- yolov8 + msrcr (multi scale retinex + color restoration)
- 97% acc
- masih deteksi betumpuk antara mi aceh & spageti wow, malah spageti wow akurasi kecil saat scan 1 object langsung
- File gabisa dibuka krn terlalu besar lol, next dipisah2 filenya
- Overfitting or model confused(?)
- Should I fine-tuning it? 🤔
- 480 ms inference

5.11.2024 :
- next add multiple object in one feature

6.11.2024 :
- Ganti metode, on process yolo NAS

15.11.2024 :
- gajadi YOLO NAS, tetap yolov8
- onnx export success (Float32)
- onnx model inference in web success
- next, test quantization
