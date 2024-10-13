<!DOCTYPE html>
<html>
<head>
    <title>Uso das Redes Sociais</title>
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
</head>
<body>
    <h1>Uso das Redes Sociais em 2024</h1>
    <canvas id="socialMediaChart"></canvas>

    <script>
        const ctx = document.getElementById('socialMediaChart').getContext('2d');
        const socialMediaChart = new Chart(ctx, {
            type: 'pie',
            data: {
                labels: ['Facebook', 'Instagram', 'Twitter', 'TikTok', 'LinkedIn'],
                datasets: [{
                    label: 'Usuários (milhões)',
                    data: [2300, 1800, 300, 1500, 900],
                    backgroundColor: ['#3b5998', '#E1306C', '#1DA1F2', '#69C9D0', '#0077B5'],
                }]
            },
            options: {
                responsive: true,
                plugins: {
                    legend: {
                        position: 'top',
                    },
                    title: {
                        display: true,
                        text: 'Usuários de Redes Sociais em Milhões (2024)'
                    }
                }
            }
        });
    </script>
</body>
</html>
