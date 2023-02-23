# htmlwithcss


<!-- creating a basic html page -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My document</title>
</head>
<style>
    body{
        background-color:darkcyan;
    }
    h1{
        text-align: center;
        background-color: burlywood;
        color: black;
        border: 2cm;
        border-radius: 40%;
        padding: 1%;
    

    }
    img{
        align-self: center;
        border-radius: 10%;
        
    }
    p{
        font-size:large;
        font-family: Georgia, 'Times New Roman', Times, serif;
        color:lightyellow;

    }
    h2{
        text-align: center;
        color:powderblue;
        font-size:250%;
    }
    .a{
        text-align: center;
    }
    ol.myol{
        text-align: center;
        display: inline-block;
        color:lightcoral;
        font-size: 150%;
    }
    ul.myul{
        text-align: center;
        display: inline-block;
        color:thistle;
        font-size: 150%;
    }
    footer{
        background-color: dimgrey;
        text-align: center;
        color:wheat;
        font-size: 200%;
        padding: 1%;
    }
</style>
<body>
    <h1>Welcome to my webpage!!</h1>
    <center><img src="https://images.unsplash.com/photo-1568144628871-ccbb00fc297c?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxzZWFyY2h8OHx8aGVsbG98ZW58MHx8MHx8&auto=format&fit=crop&w=500&q=60" alt="hey everyone!!"></center>
    <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit.<br>Saepe et vero minima suscipit dolor laudantium unde accusamus dolorum eaque beatae expedita enim consequuntur dicta voluptatum harum neque voluptatem, dolores nam.<br>
    Lorem, ipsum dolor sit amet consectetur adipisicing elit. Optio autem exercitationem reprehenderit, sapiente culpa accusamus consequatur, dolorum facere veniam aspernatur deleniti quidem, iusto praesentium ab. Velit minus at placeat tenetur!<br>
    Lorem ipsum dolor sit amet consectetur adipisicing elit. Vitae cumque laudantium praesentium illo? Ipsam atque aut voluptates maxime cupiditate impedit culpa sed. Accusantium consequuntur voluptatibus, voluptas aut animi explicabo. Exercitationem?<br></p>
    <h2>Orderd list!!</h2>
    <div class =a>
        <ol class="myol">
        <li>good morning</li>
        <li>good afternoon</li>
        <li>good evening</li>
        </ol>
    </div>
    <h2>Unordered list!!</h2>
    <div class = a>
        <ul class="myul">
        <li>hello!!</li>
        <li>haii!!</li>
        <li>namaste!!</li>
    </ul>
    </div>
    <h2>click here for audio!!</h2>
    <h1>Selenator ^^^</h1>
    <audio controls>
        <source src="Downloads/whosays.mp3" type="audio/mpeg">
      Your browser does not support the audio element.
      </audio>
      
    
</body>
<footer>
    created by Akhila Guda &hearts;&hearts;
</footer>
</html>
