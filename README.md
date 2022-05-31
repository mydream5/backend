
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Mera Chhota Projects</title>
    <link
      href="https://maxcdn.bootstrapcdn.com/bootstrap/4.1.1/css/bootstrap.min.css"
      rel="stylesheet"
      id="bootstrap-css"
    />
    <style>
     .footer{
       left: 0px;
       bottom: 0px;
       position: fixed;
       width: 100%;
       height: 50px;
       background: cyan;
       color: red;
       font-size: 20px;
       font-style: italic;
     }
      .header{
       background: hotpink;
       height: 50px;
       width: 100%;
       left: 0px;
       bottom: 0px;
       font-size: 20px;
       font-style: italic;
       color: greenyellow;
     }
      .register .nav-tabs .nav-link:hover {
        border: none;
      }
      .text-align {
        margin-top: -3%;
        margin-bottom: -9%;

        padding: 10%;
        margin-left: 30%;
      }
      .form-new {
        margin-right: 22%;
        margin-left: 20%;
      }
      .register-heading {
        margin-left: 21%;
        margin-bottom: 10%;
        color: #e9ecef;
      }
      .register-heading h1 {
        margin-left: 21%;
        margin-bottom: 10%;
        color: #e9ecef;
      }
      .register {
        background: -webkit-linear-gradient(left, #055a4f, #00c6ff);
        margin-top: 3%;
        padding: 3%;
        border-radius: 2.5rem;
      }
      .btnSubmit {
        width: 50%;
        border-radius: 1rem;
        padding: 1.5%;
        color: #fff;
        background-color: #03612e;
        border: none;
        cursor: pointer;
        margin-right: 6%;
        color: rgb(246, 246, 252);
        margin-top: 4%;
      }
    </style>
  </head>
  <body>
    <center>
        <div class="header"><center>I'm Header</center></div>
    <div class="container register">
      <div class="row">
        <div class="col-md-12">
          <div
            class="tab-pane fade show active text-align form-new"
            id="home"
            role="tabpanel"
            aria-labelledby="home-tab"
          >
            <h3 class="register-heading text-nowrap">HTML FORM</h3>
            <div class="row register-form">
              <div class="col-md-12">
                <form autocomplete="off">
                  <div class="form-group">
                    <input
                      type="text"
                      name="Name"
                      id="name"
                      class="form-control"
                      placeholder="Your Name *"
                      value=""
                      required=""
                    />
                  </div>
                  <div class="form-group">
                    <input
                      type="text"
                      name="Email"
                      id="email"
                      class="form-control"
                      placeholder="Your Email *"
                      value=""
                      required=""
                    />
                  </div>
                  <div class="form-group">
                    <input
                      type="number"
                      name="Phone"
                      id="phone"
                      class="form-control"
                      placeholder="Your Contact Number *"
                      value=""
                      required=""
                    />
                  </div>
                  <div class="form-group">
                    <select class="form-control" id="service">
                      <option>Default select</option>
                      <option>Website Development</option>
                      <option>Mobile App Development</option>
                      <option>Web and Mobile Application</option>
                    </select>
                  </div>
                  <div class="form-group">
                    <input
                      type="submit"
                      name="submit"
                      onclick="gotowhatsapp()"
                      class="btnSubmit btn-block"
                      value="Submit"
                    />
                  </div>
                </form>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
<span
class="float"
onclick="gotowhatsapp()"
style="
  position: fixed;
  width: 50px;
  height: 50px;
  bottom: 300px;
  right:  120px;
  color: #fff;
  border-radius: 50px;
  text-align: center;
  cursor: pointer;
  box-shadow: 2px 2px 3px #999;
"
>
<img
  src="https://trickuweb.com/whatsapp.png"
  alt=""
  height="60px"
  width="60px"
/>
</span>
<script>
function gotowhatsapp() {
    
    var name = document.getElementById("name").value;
    var phone = document.getElementById("phone").value;
    var email = document.getElementById("email").value;
    var service = document.getElementById("service").value;

    var url = "https://wa.me/917018392282?text=" 
    + "Name: " + name + "%0a"
    + "Phone: " + phone + "%0a"
    + "Email: " + email  + "%0a"
    + "Service: " + service; 

    window.open(url, '_blank').focus();
}
</script>

    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.1.1/js/bootstrap.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
  <p style="color: magenta;font-size: 10px;"><i><b>This project is used for backend. We will reach you directly on WhatsApp by filling this form.</b></i>
  </p>
  
          <div class="footer"><center>I'm Footer</center></div>
    </center>
  </body>
</html>

