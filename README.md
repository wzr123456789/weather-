# weather-
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/qweather-icons@1.6.0/font/qweather-icons.css">
    <link href="https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css" rel="stylesheet" />
    <link rel="stylesheet" href="">
    <title>天气查询助手</title>
    </title>
</head>

<body>
    <div class="container">
        <div class="left-info">
            <div class="pic-gradient"></div>
            <div class="today-info">
                <h2>周一</h2>
                <span>13 Apr 2024</span>
                <div>
                    <i class="bx bx-current-location"></i>
                    <span>辽宁，丹东</span>
                </div>
            </div>
            <div class="today-weather">
                <i class="qi-101 weather-icon"></i>
                <h1 class="weather-temp">17°C</h1>
                <h3>晴</h3>
            </div>
        </div>
        <div class="right-info">
            <div class="day-info">
                <div>
                    <span class="title">能见度</span>
                    <span class="value">30 公里</span>
                </div>
                <div>
                    <span class="title">湿度</span>
                    <span class="value">34 %</span>
                </div>
                <div>
                    <span class="title">风速</span>
                    <span class="value">6 km/h</span>
                </div>
            </div>
            <ul class="days-list">
                <li>
                    <i class="weather-icon qi-101"></i>
                    <span>周二</span>
                    <span class="day-temp">23°C</span>
                </li>
                 <li>
                    <i class="weather-icon qi-101"></i>
                    <span>周三</span>
                    <span class="day-temp">23°C</span>
                </li>
                 <li>
                    <i class="weather-icon qi-101"></i>
                    <span>周四</span>
                    <span class="day-temp">23°C</span>
                </li>
                 <li>
                    <i class="weather-icon qi-101"></i>
                    <span>周五</span>
                    <span class="day-temp">23°C</span>
                </li>
                <li>
                    <i class="weather-icon qi-101"></i>
                    <span>周六</span>
                    <span class="day-temp">23°C</span>
                </li>
                <li>
                    <i class="weather-icon qi-101"></i>
                    <span>周日</span>
                    <span class="day-temp">23°C</span>
                </li>
            </ul>
            <div class="btn-container">
                <button class="loc-button">搜索城市</button>
            </div>
        </div>
    </div>
<script src="script.js"></script>
</body>

</html>
