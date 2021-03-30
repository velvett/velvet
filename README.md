# velvet
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width-device-width, inital-scale-1.0">
    <title>velvet</title>
    <link href="https://fonts.googleapis.com/css2?family=Lexend:wght@500&display=swap" rel="stylesheet">
    <link rel="shortcut icon" href="C:\Users\pradith\OneDrive\Documents\Pictures\velvet-icon.jpg" type="image/x-icon">
    <link rel="stylesheet" href="https://unpkg.com/kursor/dist/kursor.css"/>
</head>
<style>
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
body{
    font-family: 'Lexend', sans-serif;
}
h1{
    font-weight: 100;
    font-size: 50px;
    letter-spacing: 40px;
    color: black;
}
h3{
    font-weight: 300;
    font-size: 100px;
    letter-spacing: 10px;   
    color: white;
}
.content{
    display: flex;
    align-items: center;
    flex-direction: column;
    text-align: center;
    justify-content: center;
    position: relative;
    height: 100vh;
}
.image-content{
    position: absolute;
    width: 100%;
    height: 100%;
    top: 0;
    left: 0;
    overflow: hidden;

}
.text-content{
    z-index: 1;
}
</style>
<body>
    
    <div class="content">
        <div class="image-content">
            <image src = "C:\Users\pradith\OneDrive\Pictures\white.jpg"></image>
        </div>
        <div class="text-content">
            <h1>velvet</h1>
            <div id="main"></div>
            </div>
        </div>
    </div>
</body>
<script src="https://unpkg.com/kursor"></script>
<script>
    new kursor({
        type: 1,
        removeDefaultCursor: true
    })
</script>
</html>
