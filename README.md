--------- Color----------
Ash: #8e8e8e;



          <div class="col-lg-12 col-md-12 m-0 p-0 text-center">
              <div class="filter">
                  <span data-filter='all' class="list active">All</span>
                  <span data-filter=".app" class="list">App Design</span>
                  <span data-filter=".web" class="list">Web Design</span>
                  <span data-filter=".ui" class="list">UI Design</span>
                  <span data-filter=".photoshop" class="list">Photoshop</span>
              </div>
          </div>

            <div class="gallery full-width">
              <div class="container">
                  <div class="row justify-content-center">
                      <div class="col-md-12 col-sm-12 col-12 p-0">
                          <div class="row">
                              <!--Single Portfolio start-->
                              <div class="col-md-4 col-sm-6 col-6 items app1 mar-bot">
                                <div class="item-img">
                                    <img src="images/p1.jpg" class="img-fluid" alt="Portfolio Image">
                                    <div class="project-icon">
                                          <a href="#"><i class="pe-7s-plus"></i></a>
                                    </div>
                                    <div class="project-title">
                                      <h3>Project Title</h3>
                                      <p>App Design</p>
                                    </div>
                                </div>
                              </div>
                              <!--Single Portfolio end-->
 
                              <!--Single Portfolio start-->
                              <div class="col-md-4 col-sm-6 col-6 items web1 mar-bot">
                                <div class="item-img">
                                    <img src="images/p2.jpg" class="img-fluid" alt="Portfolio Image">
                                    <div class="project-icon">
                                          <a href="#"><i class="pe-7s-plus"></i></a>
                                    </div>
                                    <div class="project-title">
                                      <h3>Project Title</h3>
                                      <p>App Design</p>
                                    </div>
                                </div>
                              </div>
                              <!--Single Portfolio end-->
 
                              <!--Single Portfolio start-->
                              <div class="col-md-4 col-sm-6 col-6 items ui1 mar-bot">
                                <div class="item-img">
                                    <img src="images/p3.jpg" class="img-fluid" alt="Portfolio Image">
                                    <div class="project-icon">
                                          <a href="#"><i class="pe-7s-plus"></i></a>
                                    </div>
                                    <div class="project-title">
                                      <h3>Project Title</h3>
                                      <p>App Design</p>
                                    </div>
                                </div>
                              </div>
                              <!--Single Portfolio end-->
 
                              <!--Single Portfolio start-->
                              <div class="col-md-4 col-sm-6 col-6 items photoshop1 ">
                                <div class="item-img">
                                    <img src="images/p4.jpg" class="img-fluid" alt="Portfolio Image">
                                    <div class="project-icon">
                                          <a href="#"><i class="pe-7s-plus"></i></a>
                                    </div>
                                    <div class="project-title">
                                      <h3>Project Title</h3>
                                      <p>App Design</p>
                                    </div>
                                </div>
                              </div>
                              <!--Single Portfolio end-->
 
                              <!--Single Portfolio start-->
                              <div class="col-md-4 col-sm-6 col-6 items ui1">
                                <div class="item-img">
                                    <img src="images/p5.jpg" class="img-fluid" alt="Portfolio Image">
                                    <div class="project-icon">
                                          <a href="#"><i class="pe-7s-plus"></i></a>
                                    </div>
                                    <div class="project-title">
                                      <h3>Project Title</h3>
                                      <p>App Design</p>
                                    </div>
                                </div>
                              </div>
                              <!--Single Portfolio end-->
 
                              <!--Single Portfolio start-->
                              <div class="col-md-4 col-sm-6 col-6 items app1">
                                <div class="item-img">
                                    <img src="images/p6.jpg" class="img-fluid" alt="Portfolio Image">
                                    <div class="project-icon">
                                          <a href="#"><i class="pe-7s-plus"></i></a>
                                    </div>
                                    <div class="project-title">
                                      <h3>Project Title</h3>
                                      <p>App Design</p>
                                    </div>
                                </div>
                              </div>
                              <!--Single Portfolio end-->
 
                          </div>
                      </div>                    
              </div>
          </div>
          </div>






          #service{
    background-color: #f8f8f8;
}
#service .filter{
    margin: 110px 0 30px;
}
#service .filter span{
    margin: 0 20px;
    padding: 10px;
    border: 1px solid;
    font-family: 'Roboto', sans-serif;
    text-transform: uppercase;
    cursor: pointer;
    color: #8e8e8e;
    transition: .3s;
}
#service .filter span.active{
    color: #000;
}
.work-heading h2{ 
    margin-top: 10px;
}
.mar-bot{
    margin-bottom: 25px;
}
.gallery .single-project .item-img img{
    width: 100%;
}
.item-img {
    position: relative;
    overflow: hidden;
}
.item-img img{
    width: 100%;
}
.item-img:hover img{
    transform: scale(1.2);
    transition: all 1s ease 0s;
}
.item-img::after{
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-color: #33333379;
    opacity: 0;
    transition: all 1s ease 0s;
}
.item-img:hover:after{
    opacity: 1;
    transition: all 1s ease 0s;
}
.project-icon{
    position: absolute;
    width: 100%;
    height: auto;
    top: 0;
    display: flex;
    justify-content: center;
    visibility: hidden;
    z-index: 1;
}
.item-img:hover .project-icon {
    top: 30%;
    transition: all 1s ease 0s;
    visibility: visible;
}
.project-icon a i{
    font-size: 60px;
    color: #fff;
}
.project-title{
    padding: 15px;
    background-color: #fff;
    position: absolute;
    width: 100%;
    bottom: -100%;
    opacity: 0;
    z-index: 9999;
}
.item-img:hover .project-title{
    bottom: 0;
    opacity: 1;
    transition: all 1s ease 0s;
}
.project-title p{
    margin-top: 18px;
    line-height: 0;
}