<template>
  <div>
    <!-- Breadcrumb Begin -->
    <div class="breadcrumb-option">
      <div class="container">
        <div class="row">
          <div class="col-lg-12">
            <div class="breadcrumb__links">
              <a href="./index.html"><i class="fa fa-home"></i> Home</a>
              <span>Shop</span>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- Breadcrumb End -->

    <!-- Shop Section Begin -->
    <section class="shop spad">
      <div class="container">
        <div class="row">
          <div class="col-lg-3 col-md-3">
            <div class="shop__sidebar">
              <div class="sidebar__categories">
                <div class="section-title">
                  <h4>Categories</h4>
                </div>
                <div class="categories__accordion">
                  <div class="accordion" id="accordionExample">
                    <div class="card">
                      <div class="card-heading active">
                        <a data-toggle="collapse" data-target="#collapseOne">Women</a>
                      </div>
                      <div id="collapseOne" class="collapse show" data-parent="#accordionExample">
                        <div class="card-body">
                          <ul>
                            <li><a href="#">Coats</a></li>
                            <li><a href="#">Jackets</a></li>
                            <li><a href="#">Dresses</a></li>
                            <li><a href="#">Shirts</a></li>
                            <li><a href="#">T-shirts</a></li>
                            <li><a href="#">Jeans</a></li>
                          </ul>
                        </div>
                      </div>
                    </div>
                    <div class="card">
                      <div class="card-heading">
                        <a data-toggle="collapse" data-target="#collapseTwo">Men</a>
                      </div>
                      <div id="collapseTwo" class="collapse" data-parent="#accordionExample">
                        <div class="card-body">
                          <ul>
                            <li><a href="#">Coats</a></li>
                            <li><a href="#">Jackets</a></li>
                            <li><a href="#">Dresses</a></li>
                            <li><a href="#">Shirts</a></li>
                            <li><a href="#">T-shirts</a></li>
                            <li><a href="#">Jeans</a></li>
                          </ul>
                        </div>
                      </div>
                    </div>
                    <div class="card">
                      <div class="card-heading">
                        <a data-toggle="collapse" data-target="#collapseThree">Kids</a>
                      </div>
                      <div id="collapseThree" class="collapse" data-parent="#accordionExample">
                        <div class="card-body">
                          <ul>
                            <li><a href="#">Coats</a></li>
                            <li><a href="#">Jackets</a></li>
                            <li><a href="#">Dresses</a></li>
                            <li><a href="#">Shirts</a></li>
                            <li><a href="#">T-shirts</a></li>
                            <li><a href="#">Jeans</a></li>
                          </ul>
                        </div>
                      </div>
                    </div>
                    <div class="card">
                      <div class="card-heading">
                        <a data-toggle="collapse" data-target="#collapseFour">Accessories</a>
                      </div>
                      <div id="collapseFour" class="collapse" data-parent="#accordionExample">
                        <div class="card-body">
                          <ul>
                            <li><a href="#">Coats</a></li>
                            <li><a href="#">Jackets</a></li>
                            <li><a href="#">Dresses</a></li>
                            <li><a href="#">Shirts</a></li>
                            <li><a href="#">T-shirts</a></li>
                            <li><a href="#">Jeans</a></li>
                          </ul>
                        </div>
                      </div>
                    </div>
                    <div class="card">
                      <div class="card-heading">
                        <a data-toggle="collapse" data-target="#collapseFive">Cosmetic</a>
                      </div>
                      <div id="collapseFive" class="collapse" data-parent="#accordionExample">
                        <div class="card-body">
                          <ul>
                            <li><a href="#">Coats</a></li>
                            <li><a href="#">Jackets</a></li>
                            <li><a href="#">Dresses</a></li>
                            <li><a href="#">Shirts</a></li>
                            <li><a href="#">T-shirts</a></li>
                            <li><a href="#">Jeans</a></li>
                          </ul>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
              <div class="sidebar__filter">
                <div class="section-title">
                  <h4>Shop by price</h4>
                </div>
                <div class="filter-range-wrap">
                  <div
                    class="price-range ui-slider ui-corner-all ui-slider-horizontal ui-widget ui-widget-content"
                    data-min="33"
                    data-max="99"
                  ></div>
                  <div class="range-slider">
                    <div class="price-input">
                      <p>Price:</p>
                      <input type="text" id="minamount" />
                      <input type="text" id="maxamount" />
                    </div>
                  </div>
                </div>
                <a href="#">Filter</a>
              </div>
              <div class="sidebar__sizes">
                <div class="section-title">
                  <h4>Shop by size</h4>
                </div>
                <div class="size__list">
                  <label for="xxs">
                    xxs
                    <input type="checkbox" id="xxs" />
                    <span class="checkmark"></span>
                  </label>
                  <label for="xs">
                    xs
                    <input type="checkbox" id="xs" />
                    <span class="checkmark"></span>
                  </label>
                  <label for="xss">
                    xs-s
                    <input type="checkbox" id="xss" />
                    <span class="checkmark"></span>
                  </label>
                  <label for="s">
                    s
                    <input type="checkbox" id="s" />
                    <span class="checkmark"></span>
                  </label>
                  <label for="m">
                    m
                    <input type="checkbox" id="m" />
                    <span class="checkmark"></span>
                  </label>
                  <label for="ml">
                    m-l
                    <input type="checkbox" id="ml" />
                    <span class="checkmark"></span>
                  </label>
                  <label for="l">
                    l
                    <input type="checkbox" id="l" />
                    <span class="checkmark"></span>
                  </label>
                  <label for="xl">
                    xl
                    <input type="checkbox" id="xl" />
                    <span class="checkmark"></span>
                  </label>
                </div>
              </div>
              <div class="sidebar__color">
                <div class="section-title">
                  <h4>Shop by size</h4>
                </div>
                <div class="size__list color__list">
                  <label for="black">
                    Blacks
                    <input type="checkbox" id="black" />
                    <span class="checkmark"></span>
                  </label>
                  <label for="whites">
                    Whites
                    <input type="checkbox" id="whites" />
                    <span class="checkmark"></span>
                  </label>
                  <label for="reds">
                    Reds
                    <input type="checkbox" id="reds" />
                    <span class="checkmark"></span>
                  </label>
                  <label for="greys">
                    Greys
                    <input type="checkbox" id="greys" />
                    <span class="checkmark"></span>
                  </label>
                  <label for="blues">
                    Blues
                    <input type="checkbox" id="blues" />
                    <span class="checkmark"></span>
                  </label>
                  <label for="beige">
                    Beige Tones
                    <input type="checkbox" id="beige" />
                    <span class="checkmark"></span>
                  </label>
                  <label for="greens">
                    Greens
                    <input type="checkbox" id="greens" />
                    <span class="checkmark"></span>
                  </label>
                  <label for="yellows">
                    Yellows
                    <input type="checkbox" id="yellows" />
                    <span class="checkmark"></span>
                  </label>
                </div>
              </div>
            </div>
          </div>
          <div class="col-lg-9 col-md-9">
            <div class="row">
              <div class="col-lg-3 col-md-4 col-sm-6 mix men">
                <div class="product__item">
                  <div class="product__item__pic">
                    <img src="@/assets/Customer/img/product/product-2.jpg" alt="Flowy striped skirt" />
                    <ul class="product__hover">
                      <li>
                        <a href="@/assets/Customer/img/product/product-2.jpg" class="image-popup"
                          ><span class="arrow_expand"></span
                        ></a>
                      </li>
                      <li>
                        <a href="#"><span class="icon_heart_alt"></span></a>
                      </li>
                      <li>
                        <a href="#"><span class="icon_bag_alt"></span></a>
                      </li>
                    </ul>
                  </div>
                  <div class="product__item__text">
                    <h6><a href="#">Flowy striped skirt</a></h6>
                    <div class="rating">
                      <i class="fa fa-star"></i>
                      <i class="fa fa-star"></i>
                      <i class="fa fa-star"></i>
                      <i class="fa fa-star"></i>
                      <i class="fa fa-star"></i>
                    </div>
                    <div class="product__price">$ 49.0</div>
                  </div>
                </div>
              </div>
              <div class="col-lg-3 col-md-4 col-sm-6 mix accessories">
                <div class="product__item">
                  <div class="product__item__pic">
                    <img src="@/assets/Customer/img/product/product-3.jpg" alt="Cotton T-Shirt" />
                    <div class="label stockout">out of stock</div>
                    <ul class="product__hover">
                      <li>
                        <a href="@/assets/Customer/img/product/product-3.jpg" class="image-popup"
                          ><span class="arrow_expand"></span
                        ></a>
                      </li>
                      <li>
                        <a href="#"><span class="icon_heart_alt"></span></a>
                      </li>
                      <li>
                        <a href="#"><span class="icon_bag_alt"></span></a>
                      </li>
                    </ul>
                  </div>
                  <div class="product__item__text">
                    <h6><a href="#">Cotton T-Shirt</a></h6>
                    <div class="rating">
                      <i class="fa fa-star"></i>
                      <i class="fa fa-star"></i>
                      <i class="fa fa-star"></i>
                      <i class="fa fa-star"></i>
                      <i class="fa fa-star"></i>
                    </div>
                    <div class="product__price">$ 59.0</div>
                  </div>
                </div>
              </div>
              <div class="col-lg-3 col-md-4 col-sm-6 mix cosmetic">
                <div class="product__item">
                  <div class="product__item__pic">
                    <img src="@/assets/Customer/img/product/product-4.jpg" alt="Slim striped pocket shirt" />
                    <ul class="product__hover">
                      <li>
                        <a href="@/assets/Customer/img/product/product-4.jpg" class="image-popup"
                          ><span class="arrow_expand"></span
                        ></a>
                      </li>
                      <li>
                        <a href="#"><span class="icon_heart_alt"></span></a>
                      </li>
                      <li>
                        <a href="#"><span class="icon_bag_alt"></span></a>
                      </li>
                    </ul>
                  </div>
                  <div class="product__item__text">
                    <h6><a href="#">Slim striped pocket shirt</a></h6>
                    <div class="rating">
                      <i class="fa fa-star"></i>
                      <i class="fa fa-star"></i>
                      <i class="fa fa-star"></i>
                      <i class="fa fa-star"></i>
                      <i class="fa fa-star"></i>
                    </div>
                    <div class="product__price">$ 59.0</div>
                  </div>
                </div>
              </div>
              <div class="col-lg-3 col-md-4 col-sm-6 mix kid">
                <div class="product__item">
                  <div class="product__item__pic">
                    <img src="@/assets/Customer/img/product/product-5.jpg" alt="Fit micro corduroy shirt" />
                    <ul class="product__hover">
                      <li>
                        <a href="@/assets/Customer/img/product/product-5.jpg" class="image-popup"
                          ><span class="arrow_expand"></span
                        ></a>
                      </li>
                      <li>
                        <a href="#"><span class="icon_heart_alt"></span></a>
                      </li>
                      <li>
                        <a href="#"><span class="icon_bag_alt"></span></a>
                      </li>
                    </ul>
                  </div>
                  <div class="product__item__text">
                    <h6><a href="#">Fit micro corduroy shirt</a></h6>
                    <div class="rating">
                      <i class="fa fa-star"></i>
                      <i class="fa fa-star"></i>
                      <i class="fa fa-star"></i>
                      <i class="fa fa-star"></i>
                      <i class="fa fa-star"></i>
                    </div>
                    <div class="product__price">$ 59.0</div>
                  </div>
                </div>
              </div>
              <div class="col-lg-3 col-md-4 col-sm-6 mix women men kid accessories cosmetic">
                <div class="product__item sale">
                  <div class="product__item__pic">
                    <img src="@/assets/Customer/img/product/product-6.jpg" alt="Tropical Kimono" />
                    <div class="label sale">Sale</div>
                    <ul class="product__hover">
                      <li>
                        <a href="@/assets/Customer/img/product/product-6.jpg" class="image-popup"
                          ><span class="arrow_expand"></span
                        ></a>
                      </li>
                      <li>
                        <a href="#"><span class="icon_heart_alt"></span></a>
                      </li>
                      <li>
                        <a href="#"><span class="icon_bag_alt"></span></a>
                      </li>
                    </ul>
                  </div>
                  <div class="product__item__text">
                    <h6><a href="#">Tropical Kimono</a></h6>
                    <div class="rating">
                      <i class="fa fa-star"></i>
                      <i class="fa fa-star"></i>
                      <i class="fa fa-star"></i>
                      <i class="fa fa-star"></i>
                      <i class="fa fa-star"></i>
                    </div>
                    <div class="product__price">$ 49.0 <span>$ 59.0</span></div>
                  </div>
                </div>
              </div>
              <div class="col-lg-3 col-md-4 col-sm-6 mix women men kid accessories cosmetic">
                <div class="product__item">
                  <div class="product__item__pic">
                    <img src="@/assets/Customer/img/product/product-7.jpg" alt="Contrasting sunglasses" />
                    <ul class="product__hover">
                      <li>
                        <a href="@/assets/Customer/img/product/product-7.jpg" class="image-popup"
                          ><span class="arrow_expand"></span
                        ></a>
                      </li>
                      <li>
                        <a href="#"><span class="icon_heart_alt"></span></a>
                      </li>
                      <li>
                        <a href="#"><span class="icon_bag_alt"></span></a>
                      </li>
                    </ul>
                  </div>
                  <div class="product__item__text">
                    <h6><a href="#">Contrasting sunglasses</a></h6>
                    <div class="rating">
                      <i class="fa fa-star"></i>
                      <i class="fa fa-star"></i>
                      <i class="fa fa-star"></i>
                      <i class="fa fa-star"></i>
                      <i class="fa fa-star"></i>
                    </div>
                    <div class="product__price">$ 59.0</div>
                  </div>
                </div>
              </div>
              <div class="col-lg-3 col-md-4 col-sm-6 mix women men kid accessories cosmetic">
                <div class="product__item sale">
                  <div class="product__item__pic">
                    <img src="@/assets/Customer/img/product/product-8.jpg" alt="Water resistant backpack" />
                    <div class="label">Sale</div>
                    <ul class="product__hover">
                      <li>
                        <a href="@/assets/Customer/img/product/product-8.jpg" class="image-popup"
                          ><span class="arrow_expand"></span
                        ></a>
                      </li>
                      <li>
                        <a href="#"><span class="icon_heart_alt"></span></a>
                      </li>
                      <li>
                        <a href="#"><span class="icon_bag_alt"></span></a>
                      </li>
                    </ul>
                  </div>
                  <div class="product__item__text">
                    <h6><a href="#">Water resistant backpack</a></h6>
                    <div class="rating">
                      <i class="fa fa-star"></i>
                      <i class="fa fa-star"></i>
                      <i class="fa fa-star"></i>
                      <i class="fa fa-star"></i>
                      <i class="fa fa-star"></i>
                    </div>
                    <div class="product__price">$ 49.0 <span>$ 59.0</span></div>
                  </div>
                </div>
              </div>
              <div class="col-lg-12 text-center">
                <div class="pagination__option">
                  <a href="#">1</a>
                  <a href="#">2</a>
                  <a href="#">3</a>
                  <a href="#"><i class="fa fa-angle-right"></i></a>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- Shop Section End -->
  </div>
</template>

<script>
export default {}
</script>

<style>
.product__item__pic {
  height: 300px;
  position: relative;
  overflow: hidden;
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
}

.product__item__pic img {
  width: 100%;
  height: 100%;
  object-fit: cover;
}

.categories__item {
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
  height: 100%;
  min-height: 300px;
  position: relative;
}

.categories__large__item {
  min-height: 600px;
}

.banner {
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
  height: 100%;
  min-height: 500px;
  position: relative;
}

.instagram__item {
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
  height: 100%;
  min-height: 200px;
  position: relative;
}
</style>