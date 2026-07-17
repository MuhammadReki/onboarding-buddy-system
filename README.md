# Sistem Bimbingan Akademik Berbasis RAG menggunakan Langflow

## 📋 Deskripsi
Sistem bimbingan akademik berbasis RAG (Retrieval-Augmented Generation) yang berperan sebagai Dosen Pembimbing untuk membantu mahasiswa Politeknik Pertanian Negeri Payakumbuh dalam menyelesaikan tugas akhir.

## 🛠️ Tools yang Digunakan
- Langflow
- AstraDB (Vector Database)
- Google Generative AI (Embeddings + LLM)

## 📁 Struktur Flow
1. **Read File** - Upload dokumen PDF (FAQ Mahasiswa)
2. **Split Text** - Pemotongan teks menjadi chunk
3. **Google Generative AI Embeddings** - Konversi ke vektor
4. **AstraDB** - Penyimpanan dan pencarian vektor
5. **Parser** - Konversi hasil pencarian ke konteks
6. **Prompt Template** - Template prompt "Dosen Pembimbing"
7. **Language Model** - Generasi jawaban (Gemini)
8. **Chat Output** - Output jawaban


## 🎯 Use Case
Bimbingan tugas akhir mahasiswa Politeknik Pertanian Negeri Payakumbuh

## 🚀 Cara Menggunakan
1. Import JSON ke Langflow
2. Siapkan API Key Google Generative AI
3. Upload dokumen FAQ Mahasiswa
4. Jalankan flow dan mulai bertanya

## 👤 Pembuat
Muhammad Reki

## 📅 Tanggal
Juli 2026

---
📌 *Dibuat untuk memenuhi Capstone Project IBM SkillsBuild*