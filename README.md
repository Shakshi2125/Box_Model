<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
<style>
    *{
    margin:0;
    padding:0;
    box-sizing: border-box;
}
.head, .foot{
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin:10px 35px;
    padding: 2px;
    font-size: 12px;
}
main{
    width: 100vw;
    padding: 30px;
    height: 100vh;
}
.outer, .inner, .parts, .button,.link{
    border-color: rgb(219, 43, 43);
    border-style: solid;
}
.outer{
    max-width: 556px;
    padding: 5px;
    display: flex;
    flex-direction: column;
}
.inner{
    margin: 10px;
    padding: 7px;
}

.parts{
    padding: 10px;
    
}
.para{
    display: flex;
    padding: 5px;
    align-items: center;
}
.button{
    background-color: rgb(230, 232, 234);
    
}
.button, .link{
    padding: 5px;
}
.link{
    color: #551a8b;
}
.content{
    margin-inline:3px ;
}
.foot{
    font-size: 10px;
    font-weight: 600;
}
.foot a{
    color: black;
    text-decoration: none;
}
</style>
</head>
<body>
    <header class="head">
        <div class="heading">8/25/23, 12:16 PM</div>
        <div class="heading">Box-Model.png</div>
        <div class="heading"> </div>
    </header>
    <main>
        <div class="outer">
            <div class="inner">
                <h1>I'm a box</h1>
            </div>
            <div class="inner">I'm also a box with some text in it.. Lorem ipsum, dolar sit amet consectetur adipisicing
                elit. Quod molestiae cumque dolores provident! Quo repellat odio rerum, ipsa maiores adipisci veritatis
                beatae, non ipsam minus dignissiomos amet cupiditate nesciunt quas?</div>
            <div class="inner">
                <ul>
                    <li>
                        <div class="parts">this list is a box</div>
                    </li>
                    <li>
                        <div class="parts">and all the items in it are boxes</div>
                    </li>
                </ul>
            </div>
            <div class="para">
                <div class="content">even</div>
                <div class="content button">buttons</div>
                <div class="content">and</div>
                <div class="content link"><a href="#">links</a></div>
                <div class="content">are boxes.</div>
            </div>
        </div>
    </main>
    <footer class="foot">
        <div class="footings"><a href="https://classroom.google.com/wNjEzMjg3NzA1OTUy/t/all">https://classroom.google.com/wNjEzMjg3NzA1OTUy/t/all</a></div>
        <div class="footings">1/1</div>
    </footer>
</body>
</html>