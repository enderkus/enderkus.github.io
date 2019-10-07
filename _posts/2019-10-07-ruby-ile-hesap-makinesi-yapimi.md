---
layout: post
title:  "Ruby ile Hesap Makinesi Yapımı"
categories: [ Ruby ]
image: assets/images/rubyhm.jpg
---
Ruby programlama dili günümüzdeki en hızlı gelişim gösteren ve yaygınlığını da aynı oranda sağlayan bir dildir. Ruby ile terminal üzerinden işleyen programlar geliştirebileceğiniz gibi rails ve sinatra gibi popüler web frameworkleri sayesinde web uygulamaları da geliştirebilirsiniz. Sadece bu kadar ile de kalmayıp konumuzun oluşmasına da destek sağlayan Shoes ile masaüstü uygulamalar da geliştirebilirsiniz.

Shoes, Ruby için geliştirilmiş bir grafik arayüz kütüphanesidir içerisinde kullanıma hazır element tanımlamaları bulunmaktadır. Bunları kullanarak kolaylıkla işlevsel programlar üretebiliriz. Shoes sayesinde bir kez Ruby ile programlayarak birden fazla platformda uygulamamızı çalıştırabiliriz. Ruby yükleyebildiğimiz tüm platformlarda bunu gerçekleştirebilmemiz mümkün. (Windows, Mac Os ve Linux )

Ruby kurulum aşamasını gerçekleştirdiğimizi varsayarak ilk işlemimize başlıyoruz. Shoes gem pakedini yüklemek için aşağıda belirttiğimiz komutu terminal vasıtası ile işletiyoruz.

    gem install green_shoes

Kurulum işlemi 20-25 saniye içerisinde bitecektir. Geldik şimdi programımızı yazma kısmına. Favori metin editörünüz ile hesap_makines.rb isminde bir dosya oluşturun ve içerisine aşağıda belirttiğimiz kodları uygulayın.

    require 'green_shoes'
    
    Shoes.app(title: "Hesap Makinesi", width: 200, height: 240) do
    end
