<?php
// Inisialisasi variabel untuk menyimpan hasil
$result = '';
$error = '';

// Periksa jika form telah disubmit
if ($_SERVER["REQUEST_METHOD"] == "POST") {
    $id = htmlspecialchars($_POST['id']); // Ambil ID dari input form

    // Validasi ID
    if (!empty($id) && is_numeric($id)) {
        // URL API
        $url = "https://api.rasamsetiawan1.workers.dev/nickname/ff?id=" . $id;

        // Inisialisasi cURL
        $ch = curl_init();
        curl_setopt($ch, CURLOPT_URL, $url);
        curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);

        // Eksekusi cURL dan ambil respons
        $response = curl_exec($ch);

        // Periksa apakah terjadi kesalahan
        if (curl_errno($ch)) {
            $error = 'cURL Error: ' . curl_error($ch);
        } else {
            // Decode respons JSON
            $result = json_decode($response, true);
        }

        // Tutup cURL
        curl_close($ch);
    } else {
        $error = 'ID tidak valid. Harap masukkan angka.';
    }
}
?>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nickname Finder</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #1a1a1a; /* Warna latar belakang gelap */
            color: #fff; /* Warna teks putih */
            margin: 0;
            padding: 20px;
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        h1 {
            color: #0ff; /* Warna biru cerah */
            text-shadow: 0 0 10px #00f;
        }

        form {
            background-color: #222; /* Warna latar belakang form */
            border-radius: 8px;
            padding: 20px;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.5);
            margin-bottom: 20px;
        }

        label {
            font-size: 18px;
        }

        input[type="number"] {
            width: 200px;
            padding: 10px;
            margin-top: 10px;
            border: none;
            border-radius: 5px;
            outline: none;
        }

        button {
            background-color: #0ff; /* Warna tombol biru cerah */
            color: #222; /* Warna teks tombol */
            border: none;
            border-radius: 5px;
            padding: 10px 15px;
            cursor: pointer;
            margin-top: 10px;
            font-size: 16px;
            transition: background-color 0.3s ease;
        }

        button:hover {
            background-color: #00e6e6; /* Warna saat hover */
        }

        h2 {
            margin-top: 20px;
            color: #0ff; /* Warna biru cerah untuk hasil */
            text-shadow: 0 0 10px #00f;
        }

        pre {
            background-color: #333; /* Warna latar belakang hasil */
            border-radius: 5px;
            padding: 10px;
            overflow: auto;
            color: #0f0; /* Warna teks hasil */
        }

        p {
            color: red; /* Warna teks kesalahan */
        }
    </style>
</head>
<body>
    <h1>Cari Nickname Free Fire</h1>
    <form method="post" action="">
        <label for="id">Masukkan ID:</label>
        <input type="number" id="id" name="id" required>
        <button type="submit">Cari</button>
    </form>

    <?php if ($error): ?>
        <p><?php echo $error; ?></p>
    <?php endif; ?>

    <?php if ($result): ?>
        <h2>Hasil:</h2>
        <pre><?php print_r($result); ?></pre>
    <?php endif; ?>
</body>
</html>
