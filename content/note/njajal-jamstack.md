---
title: Njajal Jamstack berbentuk Hugo
author: wongsuwung
date: '2018-09-06'
categories:
  - ngeblog
tags:
  - web
slug: njajal-jamstack-hugo
---

Jadi blog yang ente lihat ini adalah conto web yang dibuat dengan pendekatan jamstack. Jamstack setau ane selama ini, adalah arsitek web modern, yang tidak pake semacam database ato interpret kaya PHP.

Biasanya ya kalo model2 cms kaya wordpress dimana bukan bermodel jamstack -- maka ketika ada yang memuat halaman, server memproses dahulu pake php dan database kemudian baru bisa diliat, model kaya gitu kayanya gak irit sumberdaya menurut ane.

Nah beda kalo pendekatan jamstack, ini halaman digenerate menjadi statis jauh sebelum ada permintaan. Jadi kita meng-generate halaman statis dari komputer kita terus yang teruplot di server adalah halaman hasil generate berbentuk statis.

Aslinya gak semata-mata statis, karena model jamstack ini menggunakan API, jadi kalo kita mau (misalkan , masang kolom komen di blog) maka kita pake pihak API pihak-ketiga seperti disqus trus tinggal tempel di blog kita.

Engieng.. ane pake Hugo. Hugo adalah generator halaman statis. Ditulis pake bahasa Go. Opensource. sing jelas mestine gratis.

Jadi gini, ane jelasin mekanisme ane buat blog ini sehingga njedul dan terjadilah wang-xi-nawang...

Awalnya, ane download Hugo buat Windows.

Langsung dari komputer, ane jalanin Hugo, ane buat post ini dari notepad++ ... diingat-ingat lo, ini offline.

Oke ane rasa sudah tinggal save, oke ane save.

Nah, terus Hugo ini auto-detect, oww ada file baru.. preview dulu.. ow udah cocik...

Pas mau diuplot di web yang tentu online, ane menggenerate isi web keseluruhan pake Hugo.. nanti di folder public itu yang kudu diuplot. Selain itu biar di komputer masing-masing dan biar menjadi kerjaannya Hugo.

Kayanya cuma gitu setau ane, ane lagipula saat ini pas buat blog ini,nulis ini, aslinya sambil masih belajar model jamstack.

#maapmembuatmumet

Kalo ente mau tahu lebih detil dan sinambi sinau , cek web berikut buat referensi:

* jamstack.org
* staticgen.com

suwun.

