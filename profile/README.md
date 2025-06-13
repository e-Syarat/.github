## 📘 e-Syarat
E-Syarat adalah platform pembelajaran alfabet bahasa isyarat berbasis website yang dirancang secara interaktif menggunakan teknologi machine learning. Aplikasi ini dikembangkan untuk mendukung komunikasi yang lebih inklusif, dengan target pengguna mencakup masyarakat umum, keluarga penyandang tuna rungu wicara, serta komunitas tuna rungu wicara sendiri.

## 📌 Fitur

#### 1. 🖐️ Deteksi Bahasa Isyarat
- Menggunakan kamera untuk mendeteksi gerakan tangan secara **real-time**
- Terhubung ke model Machine Learning untuk mengenali gesture dan mengubahnya menjadi teks

#### 2. 🔐 Login dan Register
- Autentikasi pengguna menggunakan email dan password

#### 3. 📚 Dictionary
- Menyediakan daftar gerakan bahasa isyarat dan maknanya
- Disimpan di database dan dapat diakses melalui endpoint API
- Digunakan sebagai referensi dalam deteksi gesture

#### 4. 🧠 Quiz
- Kuis interaktif untuk menguji pemahaman pengguna terhadap bahasa isyarat

## 🚧 Status Pengembangan

| Komponen     | Status       | Platform Deploy         | Catatan                                               |
|--------------|--------------|--------------------------|--------------------------------------------------------|
| RESTful API  | ✅ Selesai    | [Railway](https://railway.app) & [Render](https://render.com) | Sudah terhubung dengan database           |
| Frontend | ✅ Selesai    | [Netlify](https://netlify.com)            | Sudah di integrasikan dengan Model Machine Learning dan API |


## 📚 Learning Resources & Tools

| Kategori           | Library / Tools                                             | IDE / Platform                     | Resource            |
|--------------------|-------------------------------------------------------------|------------------------------------|----------------------|
| **Machine Learning** | Pandas, TensorFlow, Keras, Pillow (PIL), TensorFlow.js, Numpy, Scikit-learn, Matplotlib, Seaborn, OpenCV | Jupyter Notebook, Google Colab     | Kaggle, GitHub       |
| **Frontend - Backend** | Webpack, Bootstrap, Express.js, Sequelize, MySQL          | Visual Studio Code, Insomnia, Git  | Figma, GitHub, Whimsical |


##  📖  Cara Penggunaan
- **Masuk Link : **[e-Syarat](https://e-syarat.netlify.app/)
- **Register**: Buat akun baru menggunakan username, email dan password.
- **Login**: Masuk ke akun yang sudah terdaftar untuk mengakses fitur :
- 1. **Dictionary**
- 2. **Quiz**
- 3. **Kamera untuk Deteksi Gerakan**
- 4. **About**

## 👨‍💻 Tim Development
| Nama                  | Learning Path              | Current Study                           | Role                     |
|-----------------------|----------------------------|------------------------------------------|------------------------------------------|
| Muhamad Fahmi Aulia Noor | Frontend dan Backend | Informatika @ Sekolah Tinggi Teknologi Cipasung | Backend & Project Manager|
| Muhammad Akmal Maulana   | Machine Learning | Informatika @ Universitas Siliwangi | Machine Learning engineer | 
| Zeni Ramadan           |  Frontend dan Backend | Informatika @ Sekolah Tinggi Teknologi Cipasung   | Frontend dev |
| Ayi Muhamad Nasrulloh           | Frontend dan Backend | Informatika @ Sekolah Tinggi Teknologi Cipasung | Frontend dev |
| Daffa Haidar Farras  | Machine Learning   | Informatika @ Universitas Siliwangi | Machine Learning engineer |
| Hilda Oktaviani  | Machine Learning   | Informatika @ Universitas Siliwangi | Machine Learning engineer |

## 🔁 Replika
**Jika ingin mencoba untuk mereplika project ini, Anda bisa mengikuti langkah-langkah berikut:**

### 1. 🔽 Clone Repository
- 📦 [Repo Model Machine Learning](https://github.com/e-Syarat/Machine-Learning)
- 🔧 [Repo Backend](https://github.com/e-Syarat/Back-End)
- 🎨 [Repo Frontend](https://github.com/e-Syarat/Front-End)

### 2. 📦 Install Dependensi

#### 🔧 Backend & Frontend
```bash
npm install
```
#### 🤖 Model Machine Learning
**via CMD/Terminal**
```bash
pip install -r requirements.txt
```
**via Jupyter/Google Colab**
```bash
!pip install -r requirements.txt
```
#### 🚀 Menjalankan Aplikasi
**Backend**
- untuk development
```bash
npm run dev
```
untuk production
```bash
npm run start
```
**Frontend**
- untuk development
```bash
npm run start-dev
```
untuk production
```bash
npm run build
```
**Machine Learning**
- import model
```bash
tensorflowjs_converter \
  --input_format=tf_saved_model \
  --output_format=tfjs_graph_model \
  sample_data/tf_model/ sample_data/tfjs_model/
```



