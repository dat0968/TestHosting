<template>
  <div>
    <!-- Categories Section Begin -->
    <section class="categories">
      <div class="container-fluid">
        <div class="row">
          <div class="col-lg-6 p-0">
            <div
              class="categories__item categories__large__item set-bg"
              data-setbg="../../assets/img/categories/category-1.jpg"
            >
              <div class="categories__text">
                <h1>Women's fashion</h1>
                <p>
                  Sitamet, consectetur adipiscing elit, sed do eiusmod tempor incidid-unt labore
                  edolore magna aliquapendisse ultrices gravida.
                </p>
                <a href="#">Shop now</a>
              </div>
            </div>
          </div>
          <div class="col-lg-6">
            <div class="row">
              <div class="col-lg-6 col-md-6 col-sm-6 p-0">
                <div
                  class="categories__item set-bg"
                  data-setbg="../../assets/img/categories/category-2.jpg"
                >
                  <div class="categories__text">
                    <h4>Men's fashion</h4>
                    <p>358 items</p>
                    <a href="#">Shop now</a>
                  </div>
                </div>
              </div>
              <div class="col-lg-6 col-md-6 col-sm-6 p-0">
                <div
                  class="categories__item set-bg"
                  data-setbg="../../assets/img/categories/category-3.jpg"
                >
                  <div class="categories__text">
                    <h4>Kid's fashion</h4>
                    <p>273 items</p>
                    <a href="#">Shop now</a>
                  </div>
                </div>
              </div>
              <div class="col-lg-6 col-md-6 col-sm-6 p-0">
                <div
                  class="categories__item set-bg"
                  data-setbg="../../assets/img/categories/category-4.jpg"
                >
                  <div class="categories__text">
                    <h4>Cosmetics</h4>
                    <p>159 items</p>
                    <a href="#">Shop now</a>
                  </div>
                </div>
              </div>
              <div class="col-lg-6 col-md-6 col-sm-6 p-0">
                <div
                  class="categories__item set-bg"
                  data-setbg="../../assets/img/categories/category-5.jpg"
                >
                  <div class="categories__text">
                    <h4>Accessories</h4>
                    <p>792 items</p>
                    <a href="#">Shop now</a>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- Categories Section End -->

    <!-- Product Section Begin -->
    <section class="product spad">
      <div class="container">
        <div class="row">
          <div class="col-lg-4 col-md-4">
            <div class="section-title">
              <h4>New product</h4>
            </div>
          </div>
          <div class="col-lg-8 col-md-8">
            <ul class="filter__controls">
              <li class="active" data-filter="*">All</li>
              <li data-filter=".women">Women's</li>
              <li data-filter=".men">Men's</li>
              <li data-filter=".kid">Kid's</li>
              <li data-filter=".accessories">Accessories</li>
              <li data-filter=".cosmetic">Cosmetics</li>
            </ul>
          </div>
        </div>
        <div class="row property__gallery">
          <div class="col-lg-3 col-md-4 col-sm-6 mix women">
            <div class="product__item">
              <div class="product__item__pic">
                <img src="@/assets/Customer/img/product/product-1.jpg" alt="Buttons tweed blazer" />
                <div class="label new">New</div>
                <ul class="product__hover">
                  <li>
                    <a href="@/assets/Customer/img/product/product-1.jpg" class="image-popup"
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
                <h6><a href="#">Buttons tweed blazer</a></h6>
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
        </div>
      </div>
    </section>
    <!-- Product Section End -->

    <!-- Banner Section Begin -->
    <section class="banner set-bg" data-setbg="../../assets/img/banner/banner-1.jpg">
      <div class="container">
        <div class="row">
          <div class="col-xl-7 col-lg-8 m-auto">
            <div class="banner__slider owl-carousel">
              <div class="banner__item">
                <div class="banner__text">
                  <span>The Chloe Collection</span>
                  <h1>The Project Jacket</h1>
                  <a href="#">Shop now</a>
                </div>
              </div>
              <div class="banner__item">
                <div class="banner__text">
                  <span>The Chloe Collection</span>
                  <h1>The Project Jacket</h1>
                  <a href="#">Shop now</a>
                </div>
              </div>
              <div class="banner__item">
                <div class="banner__text">
                  <span>The Chloe Collection</span>
                  <h1>The Project Jacket</h1>
                  <a href="#">Shop now</a>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- Banner Section End -->

    <!-- Trend Section Begin -->
    <section class="trend spad">
      <div class="container">
        <div class="row">
          <div class="col-lg-4 col-md-4 col-sm-6">
            <div class="trend__content">
              <div class="section-title">
                <h4>Hot Trend</h4>
              </div>
              <div class="trend__item">
                <div class="trend__item__pic">
                  <img src="../../assets/Customer/img/trend/ht-1.jpg" alt="" />
                </div>
                <div class="trend__item__text">
                  <h6>Chain bucket bag</h6>
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
              <div class="trend__item">
                <div class="trend__item__pic">
                  <img src="../../assets/Customer/img/trend/ht-2.jpg" alt="" />
                </div>
                <div class="trend__item__text">
                  <h6>Pendant earrings</h6>
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
              <div class="trend__item">
                <div class="trend__item__pic">
                  <img src="../../assets/img/trend/ht-3.jpg" alt="" />
                </div>
                <div class="trend__item__text">
                  <h6>Cotton T-Shirt</h6>
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
          </div>
          <div class="col-lg-4 col-md-4 col-sm-6">
            <div class="trend__content">
              <div class="section-title">
                <h4>Best seller</h4>
              </div>
              <div class="trend__item">
                <div class="trend__item__pic">
                  <img src="../../assets/img/trend/bs-1.jpg" alt="" />
                </div>
                <div class="trend__item__text">
                  <h6>Cotton T-Shirt</h6>
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
              <div class="trend__item">
                <div class="trend__item__pic">
                  <img src="../../assets/img/trend/bs-2.jpg" alt="" />
                </div>
                <div class="trend__item__text">
                  <h6>Zip-pockets pebbled tote <br />briefcase</h6>
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
              <div class="trend__item">
                <div class="trend__item__pic">
                  <img src="../../assets/img/trend/bs-3.jpg" alt="" />
                </div>
                <div class="trend__item__text">
                  <h6>Round leather bag</h6>
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
          </div>
          <div class="col-lg-4 col-md-4 col-sm-6">
            <div class="trend__content">
              <div class="section-title">
                <h4>Feature</h4>
              </div>
              <div class="trend__item">
                <div class="trend__item__pic">
                  <img src="../../assets/img/trend/f-1.jpg" alt="" />
                </div>
                <div class="trend__item__text">
                  <h6>Bow wrap skirt</h6>
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
              <div class="trend__item">
                <div class="trend__item__pic">
                  <img src="../../assets/img/trend/f-2.jpg" alt="" />
                </div>
                <div class="trend__item__text">
                  <h6>Metallic earrings</h6>
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
              <div class="trend__item">
                <div class="trend__item__pic">
                  <img src="../../assets/img/trend/f-3.jpg" alt="" />
                </div>
                <div class="trend__item__text">
                  <h6>Flap cross-body bag</h6>
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
          </div>
        </div>
      </div>
    </section>
    <!-- Trend Section End -->
  </div>
</template>

<script setup>
import { onMounted } from 'vue'
import category1 from '@/assets/Customer/img/categories/category-1.jpg'
import category2 from '@/assets/Customer/img/categories/category-2.jpg'
import category3 from '@/assets/Customer/img/categories/category-3.jpg'
import category4 from '@/assets/Customer/img/categories/category-4.jpg'
import category5 from '@/assets/Customer/img/categories/category-5.jpg'
import banner1 from '@/assets/Customer/img/banner/banner-1.jpg'
import insta1 from '@/assets/Customer/img/instagram/insta-1.jpg'
import insta2 from '@/assets/Customer/img/instagram/insta-2.jpg'
import insta3 from '@/assets/Customer/img/instagram/insta-3.jpg'
import insta4 from '@/assets/Customer/img/instagram/insta-4.jpg'
import insta5 from '@/assets/Customer/img/instagram/insta-5.jpg'
import insta6 from '@/assets/Customer/img/instagram/insta-6.jpg'

const setBackgroundImages = () => {
  const elements = document.querySelectorAll('[data-setbg]')
  elements.forEach((element) => {
    const bgImage = element.getAttribute('data-setbg')
    if (bgImage) {
      const imagePath = bgImage.replace('../../assets/img/', '')
      let imageUrl = ''

      switch (imagePath) {
        case 'categories/category-1.jpg':
          imageUrl = category1
          break
        case 'categories/category-2.jpg':
          imageUrl = category2
          break
        case 'categories/category-3.jpg':
          imageUrl = category3
          break
        case 'categories/category-4.jpg':
          imageUrl = category4
          break
        case 'categories/category-5.jpg':
          imageUrl = category5
          break
        case 'banner/banner-1.jpg':
          imageUrl = banner1
          break
        case 'instagram/insta-1.jpg':
          imageUrl = insta1
          break
        case 'instagram/insta-2.jpg':
          imageUrl = insta2
          break
        case 'instagram/insta-3.jpg':
          imageUrl = insta3
          break
        case 'instagram/insta-4.jpg':
          imageUrl = insta4
          break
        case 'instagram/insta-5.jpg':
          imageUrl = insta5
          break
        case 'instagram/insta-6.jpg':
          imageUrl = insta6
          break
      }

      if (imageUrl) {
        element.style.backgroundImage = `url(${imageUrl})`
      }
    }
  })
}

onMounted(() => {
  setBackgroundImages()
})
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