
Responsive Quotes built with the latest Bootstrap 5, HTML & CSS. Various variations of block quotes and quote boxes. Different styles, colors and functionalities.

Check out [Bootstrap Quotes Documentation](https://mdbootstrap.com/docs/standard/extended/quotes/) for detailed instructions & even more examples.

## Basic example

![Bootstrap 5 Quotes](https://mdbootstrap.com/img/Marketing/github/quotes/basic.png)

```html
<section class="vh-100 gradient-custom">
  <div class="container py-5 h-100">
    <div class="row d-flex justify-content-center align-items-center h-100">
      <div class="col col-xl-10">
        <div class="card">
          <div class="card-body py-5">

            <!-- Carousel wrapper -->
            <div id="carouselDarkVariant" class="carousel slide carousel-dark" data-mdb-ride="carousel">
              <!-- Indicators -->
              <div class="carousel-indicators mb-0">
                <button data-mdb-target="#carouselDarkVariant" data-mdb-slide-to="0" class="active"
                  aria-current="true" aria-label="Slide 1"></button>
                <button data-mdb-target="#carouselDarkVariant" data-mdb-slide-to="1" aria-label="Slide 1"></button>
                <button data-mdb-target="#carouselDarkVariant" data-mdb-slide-to="2" aria-label="Slide 1"></button>
              </div>

              <!-- Inner -->
              <div class="carousel-inner pt-2 pb-5">
                <!-- Single item -->
                <div class="carousel-item active">
                  <div class="row d-flex justify-content-center">
                    <div class="col-md-8 col-lg-9 col-xl-8">
                      <div class="d-flex">
                        <div class="flex-shrink-0">
                          <img src="https://mdbcdn.b-cdn.net/img/Photos/Avatars/img%20(1).webp" class="rounded-circle mb-4 mb-lg-0 shadow-2" alt="woman avatar" width="90"
                          height="90">
                        </div>
                        <div class="flex-grow-1 ms-4 ps-3">
                          <figure>
                            <blockquote class="blockquote mb-4">
                              <p>
                                <i class="fas fa-quote-left fa-lg text-warning me-2"></i>
                                <span class="font-italic">Lorem ipsum dolor sit amet consectetur adipisicing elit. Pariatur sint nesciunt ad itaque aperiam expedita officiis incidunt minus facere, molestias quisquam impedit inventore.</span>
                              </p>
                            </blockquote>
                            <figcaption class="blockquote-footer">
                              Miranda Smith in <cite title="Source Title">The Guardian</cite>
                            </figcaption>
                          </figure>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>

                <!-- Single item -->
                <div class="carousel-item">
                  <div class="row d-flex justify-content-center">
                    <div class="col-md-8 col-lg-9 col-xl-8">
                      <div class="d-flex">
                        <div class="flex-shrink-0">
                          <img src="https://mdbcdn.b-cdn.net/img/Photos/Avatars/img%20(2).webp" class="rounded-circle mb-4 mb-lg-0 shadow-2" alt="woman avatar" width="90"
                          height="90">
                        </div>
                        <div class="flex-grow-1 ms-4 ps-3">
                          <figure>
                            <blockquote class="blockquote mb-4">
                              <p>
                                <i class="fas fa-quote-left fa-lg text-warning me-2"></i>
                                <span class="font-italic">Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis.</span>
                              </p>
                            </blockquote>
                            <figcaption class="blockquote-footer">
                              Annie Hall <cite title="Source Title">New York Times</cite>
                            </figcaption>
                          </figure>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>

                <!-- Single item -->
                <div class="carousel-item">
                  <div class="row d-flex justify-content-center">
                    <div class="col-md-8 col-lg-9 col-xl-8">
                      <div class="d-flex">
                        <div class="flex-shrink-0">
                          <img src="https://mdbcdn.b-cdn.net/img/Photos/Avatars/img%20(9).webp" class="rounded-circle mb-4 mb-lg-0 shadow-2" alt="woman avatar" width="90"
                          height="90">
                        </div>
                        <div class="flex-grow-1 ms-4 ps-3">
                          <figure>
                            <blockquote class="blockquote mb-4">
                              <p>
                                <i class="fas fa-quote-left fa-lg text-warning me-2"></i>
                                <span class="font-italic">At vero eos et accusamus et iusto odio dignissimos qui blanditiis praesentium voluptatum deleniti atque corrupti quos dolores et quas molestias excepturi sint amet dolore.</span>
                              </p>
                            </blockquote>
                            <figcaption class="blockquote-footer">
                              Jason More in <cite title="Source Title">Smash Magazine</cite>
                            </figcaption>
                          </figure>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
              <!-- Inner -->

              <!-- Controls -->
              <button class="carousel-control-prev" type="button" data-mdb-target="#carouselDarkVariant"
                data-mdb-slide="prev">
                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Previous</span>
              </button>
              <button class="carousel-control-next" type="button" data-mdb-target="#carouselDarkVariant"
                data-mdb-slide="next">
                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Next</span>
              </button>
            </div>
            <!-- Carousel wrapper -->

          </div>
        </div>
      </div>
    </div>
  </div>
</section>
```

```css
.gradient-custom {
  /* fallback for old browsers */
  background: #f6d365;

  /* Chrome 10-25, Safari 5.1-6 */
  background: -webkit-linear-gradient(to right, rgba(246, 211, 101, 1), rgba(253, 160, 133, 1));

  /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */
  background: linear-gradient(to right, rgba(246, 211, 101, 1), rgba(253, 160, 133, 1))
}
```

## How to use?

1. Download MDB 5 - free UI KIT

2. Choose your favourite customized component and click on the image

3. Copy & paste the code into your MDB project

[▶️ Subscribe to YouTube channel for web development tutorials & resources](https://www.youtube.com/MDBootstrap?sub_confirmation=1)

## More examples

[Bootstrap Quotes #2:
![Bootstrap 5 Quotes](https://mdbootstrap.com/img/Marketing/github/quotes/section-2.png)](https://mdbootstrap.com/docs/standard/extended/quotes/#section-2)

[Bootstrap Quotes #3:
![Bootstrap 5 Quotes](https://mdbootstrap.com/img/Marketing/github/quotes/section-3.png)](https://mdbootstrap.com/docs/standard/extended/quotes/#section-3)

[Bootstrap Quotes #4:
![Bootstrap 5 Quotes](https://mdbootstrap.com/img/Marketing/github/quotes/section-4.png)](https://mdbootstrap.com/docs/standard/extended/quotes/#section-4)

[Bootstrap Quotes #5:
![Bootstrap 5 Quotes](https://mdbootstrap.com/img/Marketing/github/quotes/section-5.png)](https://mdbootstrap.com/docs/standard/extended/quotes/#section-5)

[Bootstrap Quotes #6:
![Bootstrap 5 Quotes](https://mdbootstrap.com/img/Marketing/github/quotes/section-6.png)](https://mdbootstrap.com/docs/standard/extended/quotes/#section-6)

[Bootstrap Quotes #7:
![Bootstrap 5 Quotes](https://mdbootstrap.com/img/Marketing/github/quotes/section-7.png)](https://mdbootstrap.com/docs/standard/extended/quotes/#section-7)

[Bootstrap Quotes #8:
![Bootstrap 5 Quotes](https://mdbootstrap.com/img/Marketing/github/quotes/section-8.png)](https://mdbootstrap.com/docs/standard/extended/quotes/#section-8)

[Bootstrap Quotes #9:
![Bootstrap 5 Quotes](https://mdbootstrap.com/img/Marketing/github/quotes/section-9.png)](https://mdbootstrap.com/docs/standard/extended/quotes/#section-9)

[Bootstrap Quotes #10:
![Bootstrap 5 Quotes](https://mdbootstrap.com/img/Marketing/github/quotes/section-10.png)](https://mdbootstrap.com/docs/standard/extended/quotes/#section-10)


___

## More extended Bootstrap documentation

<ul>
<li><a href="https://mdbootstrap.com/docs/standard/extended/bootstrap-address-form/">Bootstrap Address Form</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/avatar/">Bootstrap Avatar</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/back-to-top/">Bootstrap Back To Top Button</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/carousel-with-thumbnails/">Bootstrap Carousel Slider with Thumbnails</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/chat/">Bootstrap Chat</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/code/">Bootstrap Code Blocks</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/comments/">Bootstrap Comments</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/bootstrap-comparison-table/">Bootstrap Comparison Table</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/credit-card/">Bootstrap Credit Card Form</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/drawer/">Bootstrap Drawer</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/dropdown-multilevel/">Bootstrap Nested Dropdown</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/faq/">Bootstrap FAQ component / section</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/gallery/">Bootstrap Gallery</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/hamburger-menu/">Bootstrap Hamburger Menu</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/bootstrap-invoice/">Bootstrap Invoice</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/jumbotron/">Bootstrap Jumbotron</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/login/">Bootstrap Login Form</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/maps/">Bootstrap Maps</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/media-object/">Bootstrap Media Object</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/mega-menu/">Bootstrap Mega Menu</a></li> 
<li><a href="https://mdbootstrap.com/docs/standard/extended/multiselect/">Bootstrap Multiselect</a></li> 
<li><a href="https://mdbootstrap.com/docs/standard/extended/news-feed/">Bootstrap News Feed</a></li> 
<li><a href="https://mdbootstrap.com/docs/standard/extended/offcanvas/">Bootstrap Offcanvas</a></li> 
<li><a href="https://mdbootstrap.com/docs/standard/extended/order-details/">Bootstrap Order Details</a></li> 
<li><a href="https://mdbootstrap.com/docs/standard/extended/page-transitions/">Bootstrap Page Transitions</a></li> 
<li><a href="https://mdbootstrap.com/docs/standard/extended/payment-forms/">Bootstrap Payment Forms</a></li> 
<li><a href="https://mdbootstrap.com/docs/standard/extended/product-cards/">Bootstrap Product Cards</a></li> 
<li><a href="https://mdbootstrap.com/docs/standard/extended/profiles/">Bootstrap Profiles</a></li>  
<li><a href="https://mdbootstrap.com/docs/standard/extended/quotes/">Bootstrap Quotes</a></li> 
<li><a href="https://mdbootstrap.com/docs/standard/extended/registration/">Bootstrap Registration Form</a></li> 
<li><a href="https://mdbootstrap.com/docs/standard/extended/search-expanding/">Bootstrap Expanding Search Bar</a></li> 
<li><a href="https://mdbootstrap.com/docs/standard/extended/shopping-carts/">Bootstrap Shopping Carts</a></li> 
<li><a href="https://mdbootstrap.com/docs/standard/extended/side-navbar/">Bootstrap Side Navbar</a></li>  
<li><a href="https://mdbootstrap.com/docs/standard/extended/sidebar/">Bootstrap Sidebar</a></li>  
<li><a href="https://mdbootstrap.com/docs/standard/extended/social-media/">Bootstrap Social Media Icons & Buttons</a></li>  
<li><a href="https://mdbootstrap.com/docs/standard/extended/square-buttons/">Bootstrap Square Buttons</a></li>  
<li><a href="https://mdbootstrap.com/docs/standard/extended/bootstrap-survey-form/">Bootstrap Survey Form</a></li>  
<li><a href="https://mdbootstrap.com/docs/standard/extended/testimonial-slider/">Bootstrap Testimonial Slider</a></li>  
<li><a href="https://mdbootstrap.com/docs/standard/extended/testimonials/">Bootstrap Testimonials</a></li>  
<li><a href="https://mdbootstrap.com/docs/standard/extended/textarea/">Bootstrap Textarea</a></li>  
<li><a href="https://mdbootstrap.com/docs/standard/extended/timeline/">Bootstrap Timeline</a></li>  
<li><a href="https://mdbootstrap.com/docs/standard/extended/to-do-list/">Bootstrap To Do List</a></li>  
<li><a href="https://mdbootstrap.com/docs/standard/extended/video-carousel/">Bootstrap Video Carousel / Gallery</a></li>  
<li><a href="https://mdbootstrap.com/docs/standard/extended/weather/">Bootstrap Weather</a></li>  
</ul>

