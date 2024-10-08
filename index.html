<!DOCTYPE html>
<html lang="cs">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Blog</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <div class="container">
        <h1>Blogové příspěvky</h1>
        
        <?php
        // Připojení k databázi
        $conn = new mysqli('localhost', 'root', '', 'blog');

        // Kontrola připojení
        if ($conn->connect_error) {
            die('Připojení selhalo: ' . $conn->connect_error);
        }

        // SQL dotaz na načtení příspěvků
        $sql = "SELECT * FROM posts ORDER BY created_at DESC";
        $result = $conn->query($sql);

        // Zobrazení příspěvků
        if ($result->num_rows > 0) {
            while ($row = $result->fetch_assoc()) {
                echo "<div class='post'>";
                echo "<h2>" . $row['title'] . "</h2>";
                echo "<p>" . $row['content'] . "</p>";
                echo "<small>Publikováno: " . $row['created_at'] . "</small>";
                echo "</div>";
            }
        } else {
            echo "<p>Žádné příspěvky nejsou k dispozici.</p>";
        }

        // Uzavření připojení
        $conn->close();
        ?>
    </div>

</body>
</html>
