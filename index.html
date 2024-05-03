<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Perfect Numbers Finder</title>
    <style>
        table {
            border-collapse: collapse;
            width: 100%;
        }
        th, td {
            border: 1px solid #dddddd;
            text-align: left;
            padding: 8px;
        }
        th {
            background-color: #f2f2f2;
        }
    </style>
</head>
<body>
    <h1>Perfect Numbers Finder</h1>
    <table id="perfectNumbersTable">
        <thead>
            <tr>
                <th>Index</th>
                <th>Perfect Number</th>
            </tr>
        </thead>
        <tbody>
            <?php
            function isPrime($n) {
                if ($n <= 1) return false;
                if ($n <= 3) return true;
                if ($n % 2 == 0 || $n % 3 == 0) return false;
                $i = 5;
                while ($i * $i <= $n) {
                    if ($n % $i == 0 || $n % ($i + 2) == 0) return false;
                    $i += 6;
                }
                return true;
            }

            function mersennePrimeExponent($p) {
                return pow(2, $p) - 1;
            }

            function perfectNumber($p) {
                return (pow(2, $p - 1)) * mersennePrimeExponent($p);
            }

            $number = 2;
            $index = 1;

            while ($index <= 10) { // Change this number to adjust the number of perfect numbers displayed
                if (isPrime($number)) {
                    $mp = mersennePrimeExponent($number);
                    if (isPrime($mp)) {
                        echo "<tr><td>$index</td><td>" . perfectNumber($number) . "</td></tr>";
                        $index++;
                    }
                }
                $number++;
            }
            ?>
        </tbody>
    </table>
</body>
</html>
