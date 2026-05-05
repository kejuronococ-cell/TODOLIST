<!DOCTYPE html>  <html lang="en">  
<head>  
<meta charset="UTF-8">  
<meta name="viewport" content="width=device-width, initial-scale=1.0">  
<title>TaskMaster: An Efficient To-Do List System</title>  
<style>  
body {  
    font-family: 'Comic Sans MS', cursive;  
    background-image:url(Imagekuromi.jpg);  
    background-size: cover;  
    margin: 0;  
}  
header {  
    background-color: #16020c;  
    color: white;  
    padding: 1.5rem;  
    text-align: center;  
    font-size: 2rem;  
    border-radius: 0 0 20px 20px;  
}  
.container {  
    max-width: 700px;  
    margin: 2rem auto;  
    background-color: #fff0f5;  
    padding: 2rem;  
    border-radius: 20px;  
}  
h2 { color: #ff3399; }  
input[type="text"] {   
    padding: 10px;   
    width: 60%;   
    border-radius: 10px;   
    border: 2px solid #ff99cc;   
    margin-right: 5px;   
}  button {
background-color: #ff66b2;
color: white;
border: none;
padding: 8px 12px;
border-radius: 10px;
cursor: pointer;
}
button:hover { background-color: #ff3399; }

.task {
display: flex;
justify-content: space-between;
background: #ffe6f2;
margin-top: 10px;
padding: 10px;
border-radius: 10px;
}

/* POPUP */
.popup {
display: none;
position: fixed;
top: 0;
left: 0;
width: 100%;
height: 100%;
background: rgba(0,0,0,0.5);
justify-content: center;
align-items: center;
}
.popup:target { display: flex; }

.popup-box {
background: white;
padding: 20px;
border-radius: 15px;
width: 80%;
max-width: 300px;
text-align: center;
}

.popup-box input { width: 90%; margin-top: 10px; }

.close {
display: inline-block;
margin-top: 10px;
background: #ff66b2;
color: white;
padding: 5px 10px;
border-radius: 10px;
text-decoration: none;
}
</style>

</head>  
<body>  <header>TaskMaster: An Efficient To-Do List System</header>  <div class="container">  
    <h2>Add Task</h2>  
    <input type="text" placeholder="Enter task">  
    <button>Add Task</button>  <h2>Current Tasks</h2>  
<div class="task">  
    <span>Mag study</span>  
    <div>  
        <a href="#editPopup"><button>Edit</button></a>  
        <a href="#deletePopup"><button>Delete</button></a>  
    </div>  
</div>  
<div class="task">  
    <span>Mag assignment</span>  
    <div>  
        <a href="#editPopup"><button>Edit</button></a>  
        <a href="#deletePopup"><button>Delete</button></a>  
    </div>  
</div>  
<div class="task">  
    <span>Magdula</span>  
    <div>  
        <a href="#editPopup"><button>Edit</button></a>  
        <a href="#deletePopup"><button>Delete</button></a>  
    </div>  
</div>  

<h2>Saved Lists</h2>  
<div class="task">  
    <span><strong>Tasks</strong></span>  
    <a href="#loadPopup"><button>Load List</button></a>  
</div>  
<div style="display:flex; flex-direction:column; gap:10px; margin-top:15px;">  
    <a href="#savePopup"><button style="width:100%;">Save Current Tasks</button></a>  
    <a href="#clearPopup"><button style="width:100%;">Clear Current Tasks</button></a>  
</div>

</div>  <!-- POPUPS -->  <div id="editPopup" class="popup">  
    <div class="popup-box">  
        <h3>Edit Task</h3>  
        <input type="text" value="Clean Shop">  
        <br>  
        <a href="#" class="close">Close</a>  
    </div>  
</div>  <div id="deletePopup" class="popup">  
    <div class="popup-box">  
        <h3>Delete Task</h3>  
        <p>Are you sure?</p>  
        <div style="display:flex; justify-content:center; gap:10px; margin-top:10px;">  
            <button style="background:#ff66b2;color:white;border:none;padding:5px 10px;border-radius:10px;" disabled>Yes</button>  
            <button style="background:#ff66b2;color:white;border:none;padding:5px 10px;border-radius:10px;" disabled>No</button>  
        </div>  
        <a href="#" class="close">Close</a>  
    </div>  
</div>  <div id="loadPopup" class="popup">  
    <div class="popup-box">  
        <h3>Load List</h3>  
        <input type="text" value="Daily Tasks">  
        <br>  
        <a href="#" class="close">Close</a>  
    </div>  
</div>  <div id="savePopup" class="popup">  
    <div class="popup-box">  
        <h3>Save List</h3>  
        <input type="text" placeholder="List title">  
        <br>  
        <a href="#" class="close">Close</a>  
    </div>  
</div>  <div id="clearPopup" class="popup">  
    <div class="popup-box">  
        <h3>Clear Tasks</h3>  
        <p>Are you sure?</p>  
        <div style="display:flex; justify-content:center; gap:10px; margin-top:10px;">  
            <button style="background:#ff66b2;color:white;border:none;padding:5px 10px;border-radius:10px;" disabled>Yes</button>  
            <button style="background:#ff66b2;color:white;border:none;padding:5px 10px;border-radius:10px;" disabled>No</button>  
        </div>  
        <a href="#" class="close">Close</a>  
    </div>  
</div>  </body>  
</html>
