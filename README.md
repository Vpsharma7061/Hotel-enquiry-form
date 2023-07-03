# Hotel-enquiry-form
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>html</title>
    <style>
        body{
            color:white;
            padding: 200px;
            margin: 0px;
            background:url('images/image4.jpg');
            height:400px;
            
            background-position: center;
            background-repeat: no-repeat;
            background-size: cover;


        }
    
        
        .container{
        /* border: 3px solid rgb(214, 59, 59); */
        margin:8px 50px; /* here 106 px top se niche  ar 80 ps horizontal  */
        width:90% ;
        /* border-radius: 20px; */
        height: 600px;
    }
    h1{
        margin: 6px 60px;
        font-size: 50px;
        color: rgb(14, 8, 2);
        font-style: oblique;

    }
    h1:hover{
        color: rgb(167, 169, 35);
    }
    .form-group input {
        display: block;
        text-align: center;
        font-size: 20px;
        margin:10px 20px ;
        width: 308px;
        border-radius: 15px;
        background-color: rgb(229, 192, 192);
    }

    .form-group input:hover{
        background-color: rgb(19, 109, 79);
    }

    .container h2{
        margin: 10px 30px;
        color: rgb(129, 153, 99);
        font-size: 30px;
    }
    .groups{
        display: block;
        text-align: center;
        margin: 10px 20px;
        width: 308px;
        border-radius: 15px;
        font-size: 25px;
        background-color: rgb(206, 168, 168);
        color: rgb(104, 116, 116);
    }
    .groups:hover{
        background-color: rgb(47,105,106);
    }

    .date-Arrival{
        display: block;
        text-align: center;
        margin: 0px 15px;
        width: 308px;
        border-radius: 15px;
        font-size: 25px;
        color: rgb(104, 116, 116);
        background-color: rgb(200, 167, 167);
    }

    .date-Arrival:hover{
        background-color: rgb(47,105,106);
    }

    .date-Departure{
        display: block;
        text-align: center;
        margin: 0px 15px;
        width: 308px;
        border-radius: 15px;
        font-size: 25px;
        color: rgb(85, 111, 111);
        background-color: rgb(207, 174, 174);
    }

    .date-Departure:hover{
        background-color: rgb(47,105,106); 
    }

    .btn{
        display: block;
        text-align: center;
        margin: 0px 15px;
        width: 308px;
        border-radius: 20px;
        font-size: 30px;
        color: rgb(104, 116, 116);
       
        background-color: rgb(213, 181, 66); 
    }

    .btn:hover{
        
        background-color: rgb(117, 198, 66);  
    }


    </style>
</head>

    <!-- left box for logo  -->
    <!-- <div class="left">
    <img src="images/logo.jpg" alt="">
    <div><bold>VP FITNESS CLUB</bold></div>
    </div> -->
    <h1> WELCOME TO THE MOUNT OLIVE </h1>
    <div class="container">
        <h2>BOOKING ENQUIRY FORM  </h2>
        <form action="noaction.php">
            <div class="form-group">
                <input type="text" name="" placeholder=" Your first name ">
                <input type="text" name="" placeholder="Last name ">
            </div>
            <div class="form-group">
                <input type="text" name="" placeholder=" country ">
                
            </div>
           
            <div class="form-group">
                <input type="text" name="" placeholder=" Mobile   ">
            

            </div>
            <div class="form-group">
                <input type="text" name="" placeholder=" Identification ID  ">
            

            </div>
            <div class="form-group">
                <input type="text" name="" placeholder=" Number of adults  ">
            

            </div>
            <div class="form-group">
                <input type="text" name="" placeholder=" No.of Children aged 4-14  ">
            

            </div>

            <div class="form-group">
                <input type="text" name="" placeholder=" Number of Rooms  ">
            

            </div>

            <div class="groups">
                Select Groups: <select name="groups">
                    <option value="Family">Family</option>
                    <option value="Couple">Couple</option>
                    <option value="Friend">Friend</option>
                </select>
             </div><br>





            <div class="date-Arrival">
                
               Arrival Date :<input type="date" name="" placeholder="Arrival date">
            </div><br>
            <div class="date-Departure">
                
                Departure Date :<input type="date">
             </div><br>
             
             
             <!-- <div class="comments">
            Comments: <br><textarea name="my text" cols="50" row="80"> </textarea>
        </div> -->
            <button class="btn">Submit
            </button>

            

        </form>
        </div>





</body>

</html>
