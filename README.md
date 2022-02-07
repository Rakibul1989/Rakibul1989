<!doctype html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">
    <link rel="stylesheet" href="style.css">

    <title>Hello, world!</title>
  </head>
  <body>
    
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <div class="container-fluid">
          <a class="navbar-brand" href="#">LFWF Academy</a>

          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>

          <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav me-auto mb-2 mb-lg-0">
              <li class="nav-item">
                <a class="nav-link active" aria-current="page" href="#">Home</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">About</a>
              </li>
              <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                  Services
                </a>
                <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
                  <li><a class="dropdown-item" href="#">Action</a></li>
                  <li><a class="dropdown-item" href="#">Another action</a></li>
                  <li><hr class="dropdown-divider"></li>
                  <li><a class="dropdown-item" href="#">Something else here</a></li>
                </ul>
              </li>
              <li class="nav-item">
                <a class="nav-link ">Blog</a>
              </li>
            </ul>
            <form class="d-flex">
              <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
              <button class="btn btn-outline-success" type="submit">Search</button>
            </form>
          </div>
        </div>
      </nav>

      <div id="carouselExampleDark" class="carousel carousel-dark slide" data-bs-ride="carousel">
        <div class="carousel-indicators">
          <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
          <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="1" aria-label="Slide 2"></button>
          <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="2" aria-label="Slide 3"></button>
        </div>
        <div class="carousel-inner">
          <div class="carousel-item active" data-bs-interval="10000">
            <img src="https://i.ibb.co/4jYhT1b/landscape.jpg
            " class="d-block w-100" alt="...">
            <div class="carousel-caption d-none d-md-block">
              <h5>First slide label</h5>
              <p>Some representative placeholder content for the first slide.</p>
            </div>
          </div>
          <div class="carousel-item" data-bs-interval="2000">
            <img src="https://i.ibb.co/Dw3Y11f/lake.jpg" class="d-block w-100" alt="...">
            <div class="carousel-caption d-none d-md-block">
              <h5>Second slide label</h5>
              <p>Some representative placeholder content for the second slide.</p>
            </div>
          </div>
          <div class="carousel-item">
            <img src="https://i.ibb.co/4jYhT1b/landscape.jpg
            " class="d-block w-100" alt="...">
            <div class="carousel-caption d-none d-md-block">
              <h5>Third slide label</h5>
              <p>Some representative placeholder content for the third slide.</p>
            </div>
          </div>
        </div>
        <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleDark" data-bs-slide="prev">
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Previous</span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleDark" data-bs-slide="next">
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Next</span>
        </button>
      </div>

        <div class="container">
            <div class="row py-5 ">
                <div class="col-xl-5 ">
                    <img style="width: 380px; border: 6px double #ddd; " class="rounded" src="https://i.ibb.co/G2CvfRZ/Portrait-of-smiling-handsome-man-in-blue-t-shirt-standing-with-crossed-arms-isolated-on-grey-backgro.jpg" alt="">
                </div>
                <div class="col-xl-7">
                    <h2>Blockquotes use Korben</h2>
                    <figure>
                        <blockquote class="blockquote">
                          <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Aliquid vero nulla unde saepe explicabo ipsam nihil quia, nemo illo. Numquam, minus quae. Voluptas voluptates natus cupiditate culpa, reiciendis.</p>
                        </blockquote>
                        <blockquote class="blockquote">
                            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iure modi aspernatur molestiae delectus nemo, quis possimus velit corporis adipisci expedita cum hic! Animi.</p>
                          </blockquote>
                        <figcaption class="blockquote-footer">
                         LFWF <cite title="Source Title">Academy</cite>
                        </figcaption>
                      </figure>
                </div>
            </div>
        </div>
        <hr>
        <div class="container">
            <div class="row">
                <div class="col-xl-7">
                    <h3 class="text-success">Bootstrap5 Table</h3>
                    <table class="table table-hover">
                        <thead>
                          <tr class="table-dark">
                            <th scope="col">No</th>
                            <th scope="col">Name</th>
                            <th scope="col">Class</th>
                            <th scope="col">Roll</th>
                            <th scope="col">Section</th>
                            <th scope="col">Address</th>
                            <th scope="col">Contact</th>
                          </tr>
                        </thead>
                        <tbody>
                          <tr class="table-primary">
                            <th scope="row">1</th>
                            <td>Shahid</td>
                            <td>Ten</td>
                            <td>15</td>
                            <td>A</td>
                            <td>Dhaka</td>
                            <td>+88*******</td>
                          </tr>
                          <tr class="table-secondary">
                            <th scope="row">1</th>
                            <td>Arif</td>
                            <td>Ten</td>
                            <td>15</td>
                            <td>A</td>
                            <td>Dhaka</td>
                            <td>+88*******</td>
                          </tr>
                          <tr class="table-success text-">
                            <th scope="row">1</th>
                            <td>Hasib</td>
                            <td>Ten</td>
                            <td>15</td>
                            <td>A</td>
                            <td>Dhaka</td>
                            <td>+88*******</td>
                          </tr>
                          <tr class="table-danger">
                            <th scope="row">1</th>
                            <td>Hasib</td>
                            <td>Ten</td>
                            <td>15</td>
                            <td>A</td>
                            <td>Dhaka</td>
                            <td>+88*******</td>
                          </tr>
                          <tr class="table-warning">
                            <th scope="row">1</th>
                            <td>Hasib</td>
                            <td>Ten</td>
                            <td>15</td>
                            <td>A</td>
                            <td>Dhaka</td>
                            <td>+88*******</td>
                          </tr>
                          <tr class="table-info">
                            <th scope="row">1</th>
                            <td>Hasib</td>
                            <td>Ten</td>
                            <td>15</td>
                            <td>A</td>
                            <td>Dhaka</td>
                            <td>+88*******</td>
                          </tr>
                          <tr class="table-light">
                            <th scope="row">1</th>
                            <td>Hasib</td>
                            <td>Ten</td>
                            <td>15</td>
                            <td>A</td>
                            <td>Dhaka</td>
                            <td>+88*******</td>
                          </tr>
                          <tr class="table-primary">
                            <th scope="row">1</th>
                            <td>Hasib</td>
                            <td>Ten</td>
                            <td>15</td>
                            <td>A</td>
                            <td>Dhaka</td>
                            <td>+88*******</td>
                          </tr>
                          <tr class="table-success">
                            <th scope="row">1</th>
                            <td>Hasib</td>
                            <td>Ten</td>
                            <td>15</td>
                            <td>A</td>
                            <td>Dhaka</td>
                            <td>+88*******</td>
                          </tr>
                        </tbody>
                      </table>
                      <!-- Button trigger modal -->
<button type="button" class="btn btn-primary" data-bs-toggle="modal" data-bs-target="#exampleModal">
    Launch demo modal
  </button>
  
  <!-- Modal -->
  <div class="modal fade" id="exampleModal" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
    <div class="modal-dialog">
      <div class="modal-content">
        <div class="modal-header">
          <h5 class="modal-title" id="exampleModalLabel">Modal title</h5>
          <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
        </div>
        <div class="modal-body">
          ...
        </div>
        <div class="modal-footer">
          <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
          <button type="button" class="btn btn-primary">Save changes</button>
        </div>
      </div>
    </div>
  </div>
  
                </div>
                <div class="col-xl-5">
                    <h3 class="text-success">Bootstrap5 Form</h3>
                    <form>
                        <div class="row">
                            <div class="col-6">
                                <label for="fristname" class="form-label ">Frist Name</label> 
                                <input type="text" id="fristname" class="form-control  " placeholder="Frist Name">
                            </div>
                            <div class="col-6">
                                <label for="lastname" class="form-label ">Last Name</label>
                                <input type="text" id="lastname" class="form-control " placeholder="Last Name">
                            </div>
                        </div>
                       
                        <div class="mb-3">
                          <label for="exampleInputEmail1" class="form-label">Email address</label>
                          <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp" placeholder="name@example.com">
                         
                        </div>
                        <div class="mb-3">
                          <label for="exampleInputmessage" class="form-label">Message</label>
                          <textarea name="" id="exampleInputmessage" cols="47" rows="3" placeholder="Message"></textarea>
                        </div>
                        <div class="input-group mb-3">
                            <input type="file" class="form-control" id="inputGroupFile02">
                            
                          </div>
                          <select class="form-select form-select-lg mb-3" aria-label=".form-select-lg example">
                            <option selected>select your country</option>
                            <option value="1">Bangladesh</option>
                            <option value="2">India</option>
                            <option value="3">Pakistan</option>
                          </select>
                        <div class="mb-3 form-check">
                            <h4>Choose your Course</h4>
                          <input type="checkbox" class="form-check-input" id="exampleCheck1">
                          <label class="form-check-label" for="exampleCheck1">Web Design</label> <br>
                          <input type="checkbox" class="form-check-input" id="exampleCheck1">
                          <label class="form-check-label" for="exampleCheck1">Graphic Design</label>
                        </div>
                        <button type="submit" class="btn btn-success ">Submit</button>
                      </form>
                </div>
            </div>
        </div>
        <hr>
        <div class="container">
            <div class="row py-4">
                <h3 class="text-center pb-3">Bootstrap Card And Progress Bar</h3>
                <div class="col-xl-4">
                    <div class="card">
                        <div class="card-header text-center">
                          This is Header
                        </div>
                        <div class="card-body">
                          <h5 class="card-title">Card Title</h5>
                          <ul class="list-group list-group-flush">
                            <li class="list-group-item">This is Card list</li>
                            <li class="list-group-item">This is Card list</li>
                            <li class="list-group-item">This is Card list</li>
                            <li class="list-group-item">This is Card list</li>
                            <li class="list-group-item">This is Card list</li>
                            
                          </ul>
                          <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                          <div class="card-body">
                            <a href="#" class="card-link">Card link</a>
                            <a href="#" class="card-link">Another link</a>
                          </div>
                          <a href="#" class="btn btn-primary">Go somewhere</a>
                        </div>
                        <div class="card-footer text-center">
                            This is Footer
                          </div>
                      </div>
                </div>
                <div class="col-xl-4">
                    HTML
                    <div class="progress ">
                        <div class="progress-bar " role="progressbar" style="width: 90%;" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100">90%</div> 
                      </div> 
                      CSS
                      <div class="progress">
                        <div class="progress-bar" role="progressbar" style="width: 95%;" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100">95%</div>
                      </div> 
                      JS
                      <div class="progress">
                        <div class="progress-bar" role="progressbar" style="width: 80%;" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100">80%</div>
                      </div>
                      Bootstrap
                      <div class="progress">
                        <div class="progress-bar" role="progressbar" style="width: 85%;" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100">85%</div>
                      </div> <br>
                      <h3>text-trun cate bootstrap class use kore 3 dot anben</h3>
                      <span class="d-inline-block text-truncate" style="max-width: 350px;">
                        Praeterea iter est quasdam res quas ex communi.Praeterea iter est quasdam res quas ex communi.
                      </span> <br><br>
                      <div class="alert alert-danger" role="alert">
                        A simple danger alert—check it out!
                      </div>
                </div>
                <div class="col-xl-4">
                  <div class="card">
                    <div class="card-header text-center">
                      This is Header
                    </div>
                    <div class="card-body">
                       <img src="https://i.ibb.co/kh22p6p/card.jpg" alt="">
                      <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content card title.</p>
                      <div class="card-body">
                        
                      </div>
                    </div>
                    <div class="card-footer text-center">
                        This is Footer
                      </div>
                  </div>
                </div>
            </div>
        </div>
        <hr>

        <div class="container">
          <div class="row">
            <h3 class="text-center text-success py-4">Stretched-Link Bootstrap class use ai kaj korechi</h3>
            <div class="col-xl-4">
              <div class="card" style="width: 22rem;">
                <img src="https://i.ibb.co/0hT1nnh/blog-2.jpg" class="card-img-top" alt="...">
                <div class="card-body">
                  <h5 class="card-title">Card with stretched link</h5>
                  <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                  <a href="#" class="btn btn-primary stretched-link">Go somewhere</a>
                </div>
              </div>
            </div>
            <div class="col-xl-4">
              <div class="card" style="width: 22rem;">
                <img src="https://i.ibb.co/MCTKL78/blog-3.jpg" class="card-img-top" alt="...">
                <div class="card-body">
                  <h5 class="card-title">Card with stretched link</h5>
                  <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                  <a href="#" class="btn btn-primary stretched-link">Go somewhere</a>
                </div>
              </div>
            </div>
            <div class="col-xl-4">
              <div class="card" style="width: 22rem;">
                <img src="https://i.ibb.co/DQVX98D/blog-1.jpg" class="card-img-top" alt="...">
                <div class="card-body">
                  <h5 class="card-title">Card with stretched link</h5>
                  <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                  <a href="#" class="btn btn-primary stretched-link">Go somewhere</a>
                </div>
              </div>
            </div>
            
          </div>
        </div>
        <div class="container">
          <div class="row py-4">
            <div class="col-xl-12">
              <nav aria-label="Page navigation example py-5">
                <ul class="pagination justify-content-center">
                  <li class="page-item ">
                    <a class="page-link" href="#" tabindex="-1" aria-disabled="true">Previous</a>
                  </li>
                  <li class="page-item"><a class="page-link" href="#">1</a></li>
                  <li class="page-item"><a class="page-link" href="#">2</a></li>
                  <li class="page-item"><a class="page-link" href="#">3</a></li>
                  <li class="page-item">
                    <a class="page-link" href="#">Next</a>
                  </li>
                </ul>
              </nav>
            </div>
          </div>
        </div>
        <div class="footer text-center text-white bg-dark py-4">
          <div class="container">
            <div class="row">
              <div class="col-xl-12">
                <p>&copy;All right reserved by LFWF</p>
              </div>
            </div>
          </div>
        </div>
 

    <!-- Optional JavaScript; choose one of the two! --> 

    <!-- Option 1: Bootstrap Bundle with Popper -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>

    <!-- Option 2: Separate Popper and Bootstrap JS -->
    <!--
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.10.2/dist/umd/popper.min.js" integrity="sha384-7+zCNj/IqJ95wo16oMtfsKbZ9ccEh31eOz1HGyDuCQ6wgnyJNSYdrPa03rtR1zdB" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.min.js" integrity="sha384-QJHtvGhmr9XOIpI6YVutG+2QOK9T+ZnN4kzFN1RtK3zEFEIsxhlmWl5/YESvpZ13" crossorigin="anonymous"></script>
    -->
  </body>
</html>
