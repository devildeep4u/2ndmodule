<!DOCTYPE html>
<html lang="en">

    <head>
        <meta http-equiv="Content-Type" content="text/html; charset=utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0" />
        <meta http-equiv="X-UA-Compatible" content="ie=edge" />
        <title>:: Module 2 Assignment</title>
        <link href="https://fonts.googleapis.com/css2?family=Oxygen:wght@300&display=swap" rel="stylesheet">
        <link rel="stylesheet" href="css/module2.css">
    </head>
    body{
    font-family: 'Oxygen', sans-serif;
    font-weight: bold;
    font-style: normal;
    line-height: 1.5em;
  
}
p{
    margin-top: 3.0em;
    padding-left: 5px;
    padding-right: 5px; 
}

header {
    text-align: center;
    text-transform: capitalize;
    font-size: 1.2em;
    margin: 50px 0px; 
}
section .beef {
    border: 2px solid #000;
    background-color: #D3D3DE;
    height: auto;
    position: relative;
    width: 31%;
    height: auto;
    float: left;
    margin: 0px 10px;
    padding: 0px;

}

section .chicken {
    border: 2px solid #000;
    background-color: #D3D3DE;
    height: auto;
    position: relative;
    width: 31%;
    height: auto;
    float: left;
    margin: 0px 10px 0px 18px;
    padding: 0px;
}
section .sushi {
    border: 2px solid #000;
    background-color: #D3D3DE;
    height: auto;
    position: relative;
    width: 31%;
    height: auto;
    float: left;
    margin: 0px 10px;
    padding: 0px;
}

 h4{
    text-align: center;
    border: 1px solid #000;
    padding: 5px; 
    width: 20%; 
    top: 0;
    right: 0;
    clear: left;
    position: absolute;
    margin-top: 0;
}

    
.beef > h4{
    background-color: #cfdd0f;
  }
.chicken > h4{
    background-color: pink;
}
.sushi > h4{
    background-color: burlywood;
}


@media(min-width: 992px){
    section .beef {
        border: 2px solid #000;
        background-color: #D3D3DE;
        height: auto;
        position: relative;
        width: 30%;
        height: auto;
        float: left;
        margin: 0px 10px;
        padding: 0px;
    
    }
    
    section .chicken {
        border: 2px solid #000;
        background-color: #D3D3DE;
        height: auto;
        position: relative;
        width: 30%;
        height: auto;
        float: left;
        margin: 0px 10px;
        padding: 0px;
    }
    section .sushi {
        border: 2px solid #000;
        background-color: #D3D3DE;
        height: auto;
        position: relative;
        width: 30%;
        height: auto;
        margin: 0px 10px;
        padding: 0px;
    }
}

@media(min-width: 768px) and (max-width: 991px){
    section .beef {
        border: 2px solid #000;
        background-color: #D3D3DE;
        height: auto;
        position: relative;
        width: 46%;
        height: auto;
        margin: 0px 10px 5px 10px;
        padding: 0px;
    
    }
    
    section .chicken {
        border: 2px solid #000;
        background-color: #D3D3DE;
        height: auto;
        position: relative;
        width: 46%;
        height: auto;
        float: left;
        margin: 0px 10px 5px 10px;
        padding: 0px;
    }
    section .sushi {
        border: 2px solid #000;
        background-color: #D3D3DE;
        height: auto;
        position: relative;
        width: 96%;
        height: auto;
        float: left;
        margin: 10px 10px;
        padding: 0px;
    }
}
@media(max-width: 767px){
    section .beef {
        border: 2px solid #000;
        background-color: #D3D3DE;
        height: auto;
        position: relative;
        width: 97%;
        height: auto;
        margin: 10px;
        padding: 0px;
    
    }
    
    section .chicken {
        border: 2px solid #000;
        background-color: #D3D3DE;
        height: auto;
        position: relative;
        width: 97%;
        height: auto;
        margin: 10px;
        padding: 0px;
    }
    section .sushi {
        border: 2px solid #000;
        background-color: #D3D3DE;
        height: auto;
        position: relative;
        width: 97%;
        height: auto;
        margin: 10px;
        padding: 0px;
    }
}

    <body>
        <header>
            <h2>Our Menu</h2>
        </header>
        <section>
            <div class="chicken">
                <h4>Chicken</h4>
                <div>
                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris convallis justo elit, sit amet
                        aliquet felis placerat quis.
                        Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas.
                        Phasellus sed augue cursus,
                        vulputate libero ut, volutpat dui. </p>
                </div>
            </div>
        </section>
        <section>
            <div class="beef">
                <h4>Beef</h4>
                <div>
                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris convallis justo elit, sit amet
                        aliquet felis placerat quis.
                        Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas.
                        Phasellus sed augue cursus,
                        vulputate libero ut, volutpat dui. </p>
                </div>
            </div>
        </section>
        <section>
            <div class="sushi">
                <h4>Sushi</h4>
                <div>
                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris convallis justo elit, sit amet
                        aliquet felis placerat quis.
                        Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas.
                        Phasellus sed augue cursus,
                        vulputate libero ut, volutpat dui. </p>
                </div>
            </div>
        </section>

    </body>

</html>
