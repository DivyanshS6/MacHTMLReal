# MacHTMLReal

<!DOCTYPE html> 
<html>
    <head>
        <title>Websit</title>
    </head>
    <body>
        <h1>
            websit ish epik
        </h1>
        <p> website stuff is cool</p>
        <img src="https://cdn.pixabay.com/photo/2023/04/17/07/26/ai-generated-7931805_960_720.jpg">
        <blockquote> "life is life" </blockquote>

        <button onclick="changeQuote()">Change Quote</button>

        <script>
            var index = 0;

            function changeQuote() {
                var quotes = [
                    `"if you sit, you are sitting." - Divyansh Shukla`, 
                    `"if you decide to get up, you are standing" - Divyansh Shukla`,
                    `"to stand or not to stand, that is the question" - Divyansh Shukla`,
                    `"to sit again, or not to sit again, that is the question" - Divyansh Shukla`

                ];
                var blockquote = document.querySelector("blockquote");
                blockquote.innerHTML = quotes[index];

                index++;
                if (index >= 4) {
                    index = 0;
                }
            }

        </script>

    </body>
</html>
