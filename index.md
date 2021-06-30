---
title: Instruksi yang Dihosting Online
permalink: index.html
layout: home
---

# Latihan Dasar-Dasar AI Azure

Repositori ini berisi latihan lab langsung untuk kursus Microsoft [AI-900 *Kecerdasan Buatan Microsoft Azure*](https://docs.microsoft.com/id-id/learn/certifications/courses/ai-900t00) dan modul mandiri yang setara di Microsoft Learn: [Memulai dengan kecerdasan buatan di Azure](https://docs.microsoft.com/learn/paths/get-started-with-artificial-intelligence-on-azure/), [Membuat model prediktif tanpa kode dengan Azure Machine Learning](https://docs.microsoft.com/id-id/learn/paths/create-no-code-predictive-models-azure-machine-learning/),  [Menjelajahi Visi Komputer di Microsoft Azure](https://docs.microsoft.com/learn/paths/explore-computer-vision-microsoft-azure/), [Menjelajahi pemrosesan bahasa alami](https://docs.microsoft.com/learn/paths/explore-natural-language-processing/), dan [Menjelajahi AI percakapan](https://docs.microsoft.com/learn/paths/explore-conversational-ai/). Latihan ini didesain untuk melengkapi materi pembelajaran dan memungkinkan Anda mempraktikkan teknologi yang dijelaskan. 

Untuk menyelesaikan latihan ini, Anda harus berlangganan Microsoft Azure Jika instruktur tidak menyediakannya, Anda dapat mendaftar uji coba gratis di [https://azure.microsoft.com](https://azure.microsoft.com).

{% assign labs = site.pages | where_exp:"page", "page.url contains '/instructions'" %}
| Latihan |
| ------- | 
{% for activity in labs  %}| [{{ activity.lab.title }}]({{ site.github.url }}{{ activity.url }}) |
{% endfor %}
