# Site-217-Lojistik-Talep-Sistemi
Bu Sitenin Amacı Site 217 Lojistik Talep İçindir 
<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <title>Site 217 | Lojistik</title>

    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: #080b0f;
            color: white;
        }

        .anasayfa {
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
        }

        h1 {
            font-size: 42px;
            margin-bottom: 10px;
        }

        p {
            color: #9ca3aa;
        }

        .buton {
            margin-top: 25px;
            padding: 15px 30px;
            background: #d71920;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
        }

        .form-alani {
            max-width: 700px;
            margin: 0 auto;
            padding: 80px 20px;
        }

        .form-kutu {
            background: #11161c;
            padding: 30px;
            border: 1px solid #303840;
            border-radius: 8px;
        }

        label {
            display: block;
            margin-top: 18px;
            margin-bottom: 7px;
            color: #cfd4d8;
        }

        input, textarea, select {
            width: 100%;
            box-sizing: border-box;
            padding: 12px;
            background: #080b0f;
            border: 1px solid #3b424a;
            color: white;
            border-radius: 4px;
        }

        textarea {
            min-height: 120px;
            resize: vertical;
        }

        button {
            width: 100%;
            margin-top: 25px;
            padding: 14px;
            background: #d71920;
            color: white;
            border: none;
            border-radius: 4px;
            font-weight: bold;
            cursor: pointer;
        }
    </style>
</head>

<body>

    <section class="anasayfa">
        <h1>SITE 217</h1>
        <p>Lojistik Departmanı</p>

        <a href="#lojistik-formu" class="buton">
            LOJİSTİK TALEBİ OLUŞTUR
        </a>
    </section>


    <section id="lojistik-formu" class="form-alani">

        <div class="form-kutu">

            <h2>Lojistik Talep Formu</h2>
            <p>Talebinizi eksiksiz şekilde doldurunuz.</p>

            <form>

                <label>Talep Eden</label>
                <input type="text" placeholder="Ad / Kullanıcı adı">

                <label>Talep Edilen</label>
                <input type="text" placeholder="Talep edilen malzeme">

                <label>Talep Edilen Miktar</label>
                <input type="number" placeholder="Miktar">

                <label>Talep Nedeni</label>
                <textarea placeholder="Talebin nedenini açıklayınız"></textarea>

                <label>Kullanılacak Birim / Departman</label>
                <select>
                    <option>Departman seçiniz</option>
                    <option>Güvenlik</option>
                    <option>İç Güvenlik</option>
                    <option>Medikal</option>
                    <option>Bilimsel</option>
                    <option>Omega-1</option>
                    <option>Site Direktörlüğü</option>
                </select>

                <label>Ek Açıklama</label>
                <textarea placeholder="Varsa ek bilgiler"></textarea>

                <button type="submit">
                    TALEBİ GÖNDER
                </button>

            </form>

        </div>

    </section>

</body>
</html>
