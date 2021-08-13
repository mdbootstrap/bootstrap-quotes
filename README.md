# Bootstrap Quotes

Responsive Quotes built with the latest Bootstrap 5, HTML & CSS. Various variations of block quotes and quote boxes. Different styles, colors and functionalities.

## Basic example

HTML

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
                          <img src="https://mdbootstrap.com/img/Photos/Avatars/img%20(1).jpg" class="rounded-circle mb-4 mb-lg-0 shadow-2" alt="woman avatar" width="90"
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
                          <img src="https://mdbootstrap.com/img/Photos/Avatars/img%20(2).jpg" class="rounded-circle mb-4 mb-lg-0 shadow-2" alt="woman avatar" width="90"
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
                          <img src="https://mdbootstrap.com/img/Photos/Avatars/img%20(9).jpg" class="rounded-circle mb-4 mb-lg-0 shadow-2" alt="woman avatar" width="90"
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

CSS
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

#### Much more examples and a detailed description can be found at [📄 Quotes documentation page](https://mdbootstrap.com/docs/standard/extended/quotes/)
