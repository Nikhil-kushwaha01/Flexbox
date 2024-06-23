<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Task 4</title>
    <link href="https://fonts.googleapis.com/css2?family=Open+Sans:wght@400;600;700&family=Poppins:wght@700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Open Sans', sans-serif;
            margin: 0;
            padding: 0;
            background-color: hsl(207, 100%, 98%);
            color: hsl(192, 100%, 9%);
        }
        h1, h2, h3 {
            font-family: 'Poppins', sans-serif;
            font-weight: 700;
        }
        header, footer {
            text-align: center;
            padding: 20px;
            background-color: hsl(322, 100%, 66%);
            color: white;
        }
        .content {
            padding: 20px;
            text-align: center;
        }
        .cta {
            background-color: hsl(322, 100%, 66%);
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
            display: inline-block;
        }
        .statistics {
            display: flex;
            justify-content: space-around;
            margin: 20px 0;
        }
        .stat {
            text-align: center;
        }
        footer {
            margin-top: 20px;
        }
        a {
            color: white;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
        @media (max-width: 375px) {
            .statistics {
                flex-direction: column;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Try it free</h1>
    </header>
    <div class="content">
        <h2>Build The Community Your Fans Will Love</h2>
        <p>Huddle re-imagines the way we build communities. You have a voice, but so does your audience. Create connections with your users as you engage in genuine discussion.</p>
        <a href="#" class="cta">Get Started For Free</a>
        <div class="statistics">
            <div class="stat">
                <h3>1.4k+</h3>
                <p>Communities Formed</p>
            </div>
            <div class="stat">
                <h3>2.7m+</h3>
                <p>Messages Sent</p>
            </div>
        </div>
        <h2>Grow Together</h2>
        <p>Generate meaningful discussions with your audience and build a strong, loyal community. Think of the insightful conversations you miss out on with a feedback form.</p>
        <h2>Flowing Conversations</h2>
        <p>You wouldn't paginate a conversation in real life, so why do it online? Our threads have just-in-time loading for a more natural flow.</p>
        <h2>Your Users</h2>
        <p>It takes no time at all to integrate Huddle with your app's authentication solution. This means, once signed in to your app, your users can start chatting immediately.</p>
        <h2>Ready To Build Your Community?</h2>
        <a href="#" class="cta">Get Started For Free</a>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris nulla quam, hendrerit lacinia vestibulum a, ultrices quis sem.</p>
        <p>Phone: +1-543-123-4567<br>example@huddle.com</p>
        <h2>Newsletter</h2>
        <p>To receive tips on how to grow your community, sign up to our weekly newsletter. We’ll never send you spam or pass on your email address.</p>
        <a href="#" class="cta">Subscribe</a>
    </div>
    <footer>
        Coded by <a href="#">Nikhil Kushwaha</a>.
    </footer>
</body>
</html>
