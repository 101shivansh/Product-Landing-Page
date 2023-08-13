# Product-Landing-Page

<!--INDEX.HTML-->

<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Dexter FootWear</title>
  <link rel="shortcut icon" href="dexter logo.jpg" type="image/svg+xml">
  
  <link rel="stylesheet" href="./assets/css/style.css">

  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link
    href="https://fonts.googleapis.com/css2?family=Josefin+Sans:wght@300;400;500;600;700&family=Roboto:wght@400;500;700&display=swap"
    rel="stylesheet">

  <link rel="preload" href="./assets/images/hero-banner.png" as="image">
</head>

<body id="top">

  <header class="header" data-header>
    <div class="container">
      <div class="overlay" data-overlay></div>

      <a href="#" class="logo">
        <img src="./assets/images/logo.png" width="250" height="50" alt="Pinaki FootWare logo">
      </a>

      <button class="nav-open-btn" data-nav-open-btn aria-label="Open Menu">
        <ion-icon name="menu-outline"></ion-icon>
      </button>

      <nav class="navbar" data-navbar>

        <button class="nav-close-btn" data-nav-close-btn aria-label="Close Menu">
          <ion-icon name="close-outline"></ion-icon>
        </button>

        <a href="#" class="logo">
          <img src="./assets/images/logo.png" width="250" height="50" alt="Dexter FootWare logo">
        </a>

        <ul class="navbar-list">

          <li class="navbar-item">
            <a href="#" class="navbar-link">Home</a>
          </li>

          <li class="navbar-item">
            <a href="#" class="navbar-link">About</a>
          </li>

          <li class="navbar-item">
            <a href="#" class="navbar-link">Products</a>
          </li>

          <li class="navbar-item">
            <a href="#" class="navbar-link">Shop</a>
          </li>

          <li class="navbar-item">
            <a href="#" class="navbar-link">Blog</a>
          </li>

          <li class="navbar-item">
            <a href="#" class="navbar-link">Contact</a>
          </li>
        </ul>
        
        <ul class="nav-action-list">
          <li>
            <button class="nav-action-btn">
              <ion-icon name="search-outline" aria-hidden="true"></ion-icon>

              <span class="nav-action-text">Search</span>
            </button>
          </li>

          <li>
            <a href="#" class="nav-action-btn">
              <ion-icon name="person-outline" aria-hidden="true"></ion-icon>

              <span class="nav-action-text">Login / Register</span>
            </a>
          </li>

          <li>
            <button class="nav-action-btn">
              <ion-icon name="heart-outline" aria-hidden="true"></ion-icon>

              <span class="nav-action-text">Wishlist</span>

              <data class="nav-action-badge" value="5" aria-hidden="true">5</data>
            </button>
          </li>

          <li>
            <button class="nav-action-btn">
              <ion-icon name="bag-outline" aria-hidden="true"></ion-icon>

              <data class="nav-action-text" value="₹ 318.00">Basket: <strong>₹ 318.00</strong></data>

              <data class="nav-action-badge" value="4" aria-hidden="true">4</data>
            </button>
          </li>
        </ul>
      </nav>
    </div>
  </header>

  <main>
    <article>

      <section class="section hero" style="background-image: url('./assets/images/hero-banner.png')">
        <div class="container">

          <h2 class="h1 hero-title">
            New Summer <strong>Shoes Collection</strong>
          </h2>

          <p class="hero-text">
          Favourite footwear for Summer days & cool evenings. Pair with our latest styles. To be happy, it first takes being comfortable being in your own shoes. The rest can work up from there.
          </p>

          <button class="btn btn-primary">
            <span>Shop Now</span>

            <ion-icon name="arrow-forward-outline" aria-hidden="true"></ion-icon>
          </button>

        </div>
      </section>

      <section class="section collection">
        <div class="container">

          <ul class="collection-list has-scrollbar">

            <li>
              <div class="collection-card" style="background-image: url('./assets/images/collection-1.jpg')">
                <h3 class="h4 card-title">Men Collections</h3>

                <a href="index2.html" class="btn btn-secondary">
                  <span>Explore All</span>

                  <ion-icon name="arrow-forward-outline" aria-hidden="true"></ion-icon>
                </a>
              </div>
            </li>

            <li>
              <div class="collection-card" style="background-image: url('./assets/images/collection-2.jpg')">
                <h3 class="h4 card-title">Women Collections</h3>

                <a href="index2.html" class="btn btn-secondary">
                  <span>Explore All</span>

                  <ion-icon name="arrow-forward-outline" aria-hidden="true"></ion-icon>
                </a>
              </div>
            </li>

            <li>
              <div class="collection-card" style="background-image: url('./assets/images/collection-3.jpg')">
                <h3 class="h4 card-title">Sports Collections</h3>

                <a href="index2.html" class="btn btn-secondary">
                  <span>Explore All</span>

                  <ion-icon name="arrow-forward-outline" aria-hidden="true"></ion-icon>
                </a>
              </div>
            </li>

          </ul>

        </div>
      </section>

      <section class="section product">
        <div class="container">

          <h2 class="h2 section-title">Bestsellers Products</h2>
          <ul class="filter-list">

            <li>
              <button class="filter-btn  active">All</button>
            </li>

            <li>
              <button class="filter-btn">Nike</button>
            </li>

            <li>
              <button class="filter-btn">Adidas</button>
            </li>

            <li>
              <button class="filter-btn">Puma</button>
            </li>

            <li>
              <button class="filter-btn">Bata</button>
            </li>

            <li>
              <button class="filter-btn">Apex</button>
            </li>
          </ul>

          <ul class="product-list">
            <li class="product-item">
              <div class="product-card" tabindex="0">

                <figure class="card-banner">
                  <img src="./assets/images/product-1.jpg" width="312" height="350" loading="lazy"
                    alt="Running Sneaker Shoes" class="image-contain">

                  <div class="card-badge">New</div>

                  <ul class="card-action-list">

                    <li class="card-action-item">
                      <button class="card-action-btn" aria-labelledby="card-label-1">
                        <ion-icon name="cart-outline"></ion-icon>
                      </button>

                      <div class="card-action-tooltip" id="card-label-1">Add to Cart</div>
                    </li>

                    <li class="card-action-item">
                      <button class="card-action-btn" aria-labelledby="card-label-2">
                        <ion-icon name="heart-outline"></ion-icon>
                      </button>

                      <div class="card-action-tooltip" id="card-label-2">Add to Whishlist</div>
                    </li>

                    <li class="card-action-item">
                      <button class="card-action-btn" aria-labelledby="card-label-3">
                        <ion-icon name="eye-outline"></ion-icon>
                      </button>

                      <div class="card-action-tooltip" id="card-label-3">Quick View</div>
                    </li>

                    <li class="card-action-item">
                      <button class="card-action-btn" aria-labelledby="card-label-4">
                        <ion-icon name="repeat-outline"></ion-icon>
                      </button>

                      <div class="card-action-tooltip" id="card-label-4">Compare</div>
                    </li>

                  </ul>
                </figure>

                <div class="card-content">

                  <div class="card-cat">
                    <a href="#" class="card-cat-link">Men</a> /
                    <a href="#" class="card-cat-link">Women</a>
                  </div>

                  <h3 class="h3 card-title">
                    <a href="#">Running Sneaker Shoes</a>
                  </h3>

                  <data class="card-price" value="180.85">₹ 180.85</data>

                </div>

              </div>
            </li>

            <li class="product-item">
              <div class="product-card" tabindex="0">

                <figure class="card-banner">
                  <img src="./assets/images/product-2.jpg" width="312" height="350" loading="lazy"
                    alt="Leather Mens Slipper" class="image-contain">

                  <ul class="card-action-list">

                    <li class="card-action-item">
                      <button class="card-action-btn" aria-labelledby="card-label-1">
                        <ion-icon name="cart-outline"></ion-icon>
                      </button>

                      <div class="card-action-tooltip" id="card-label-1">Add to Cart</div>
                    </li>

                    <li class="card-action-item">
                      <button class="card-action-btn" aria-labelledby="card-label-2">
                        <ion-icon name="heart-outline"></ion-icon>
                      </button>

                      <div class="card-action-tooltip" id="card-label-2">Add to Whishlist</div>
                    </li>

                    <li class="card-action-item">
                      <button class="card-action-btn" aria-labelledby="card-label-3">
                        <ion-icon name="eye-outline"></ion-icon>
                      </button>

                      <div class="card-action-tooltip" id="card-label-3">Quick View</div>
                    </li>

                    <li class="card-action-item">
                      <button class="card-action-btn" aria-labelledby="card-label-4">
                        <ion-icon name="repeat-outline"></ion-icon>
                      </button>

                      <div class="card-action-tooltip" id="card-label-4">Compare</div>
                    </li>

                  </ul>
                </figure>

                <div class="card-content">

                  <div class="card-cat">
                    <a href="#" class="card-cat-link">Men</a> /
                    <a href="#" class="card-cat-link">Sports</a>
                  </div>

                  <h3 class="h3 card-title">
                    <a href="#">Leather Mens Slipper</a>
                  </h3>

                  <data class="card-price" value="190.85">₹ 190.85</data>

                </div>

              </div>
            </li>

            <li class="product-item">
              <div class="product-card" tabindex="0">

                <figure class="card-banner">
                  <img src="./assets/images/product-3.jpg" width="312" height="350" loading="lazy"
                    alt="Simple Fabric Shoe" class="image-contain">

                  <div class="card-badge">New</div>

                  <ul class="card-action-list">

                    <li class="card-action-item">
                      <button class="card-action-btn" aria-labelledby="card-label-1">
                        <ion-icon name="cart-outline"></ion-icon>
                      </button>

                      <div class="card-action-tooltip" id="card-label-1">Add to Cart</div>
                    </li>

                    <li class="card-action-item">
                      <button class="card-action-btn" aria-labelledby="card-label-2">
                        <ion-icon name="heart-outline"></ion-icon>
                      </button>

                      <div class="card-action-tooltip" id="card-label-2">Add to Whishlist</div>
                    </li>

                    <li class="card-action-item">
                      <button class="card-action-btn" aria-labelledby="card-label-3">
                        <ion-icon name="eye-outline"></ion-icon>
                      </button>

                      <div class="card-action-tooltip" id="card-label-3">Quick View</div>
                    </li>

                    <li class="card-action-item">
                      <button class="card-action-btn" aria-labelledby="card-label-4">
                        <ion-icon name="repeat-outline"></ion-icon>
                      </button>

                      <div class="card-action-tooltip" id="card-label-4">Compare</div>
                    </li>

                  </ul>
                </figure>

                <div class="card-content">

                  <div class="card-cat">
                    <a href="#" class="card-cat-link">Men</a> /
                    <a href="#" class="card-cat-link">Women</a>
                  </div>

                  <h3 class="h3 card-title">
                    <a href="#">Simple Fabric Shoe</a>
                  </h3>

                  <data class="card-price" value="160.85">₹160.85</data>

                </div>

              </div>
            </li>

            <li class="product-item">
              <div class="product-card" tabindex="0">

                <figure class="card-banner">
                  <img src="./assets/images/product-4.jpg" width="312" height="350" loading="lazy"
                    alt="Air Jordan 7 Retro " class="image-contain">

                  <div class="card-badge"> -25%</div>

                  <ul class="card-action-list">

                    <li class="card-action-item">
                      <button class="card-action-btn" aria-labelledby="card-label-1">
                        <ion-icon name="cart-outline"></ion-icon>
                      </button>

                      <div class="card-action-tooltip" id="card-label-1">Add to Cart</div>
                    </li>

                    <li class="card-action-item">
                      <button class="card-action-btn" aria-labelledby="card-label-2">
                        <ion-icon name="heart-outline"></ion-icon>
                      </button>

                      <div class="card-action-tooltip" id="card-label-2">Add to Whishlist</div>
                    </li>

                    <li class="card-action-item">
                      <button class="card-action-btn" aria-labelledby="card-label-3">
                        <ion-icon name="eye-outline"></ion-icon>
                      </button>

                      <div class="card-action-tooltip" id="card-label-3">Quick View</div>
                    </li>

                    <li class="card-action-item">
                      <button class="card-action-btn" aria-labelledby="card-label-4">
                        <ion-icon name="repeat-outline"></ion-icon>
                      </button>

                      <div class="card-action-tooltip" id="card-label-4">Compare</div>
                    </li>

                  </ul>
                </figure>

                <div class="card-content">

                  <div class="card-cat">
                    <a href="#" class="card-cat-link">Men</a> /
                    <a href="#" class="card-cat-link">Sports</a>
                  </div>

                  <h3 class="h3 card-title">
                    <a href="#">Air Jordan 7 Retro </a>
                  </h3>

                  <data class="card-price" value="170.85">₹ 170.85 <del>₹ 200.21</del></data>

                </div>

              </div>
            </li>

            <li class="product-item">
              <div class="product-card" tabindex="0">

                <figure class="card-banner">
                  <img src="./assets/images/product-5.jpg" width="312" height="350" loading="lazy"
                    alt="Nike Air Max 270 SE" class="image-contain">

                  <div class="card-badge">New</div>

                  <ul class="card-action-list">

                    <li class="card-action-item">
                      <button class="card-action-btn" aria-labelledby="card-label-1">
                        <ion-icon name="cart-outline"></ion-icon>
                      </button>

                      <div class="card-action-tooltip" id="card-label-1">Add to Cart</div>
                    </li>

                    <li class="card-action-item">
                      <button class="card-action-btn" aria-labelledby="card-label-2">
                        <ion-icon name="heart-outline"></ion-icon>
                      </button>

                      <div class="card-action-tooltip" id="card-label-2">Add to Whishlist</div>
                    </li>

                    <li class="card-action-item">
                      <button class="card-action-btn" aria-labelledby="card-label-3">
                        <ion-icon name="eye-outline"></ion-icon>
                      </button>

                      <div class="card-action-tooltip" id="card-label-3">Quick View</div>
                    </li>

                    <li class="card-action-item">
                      <button class="card-action-btn" aria-labelledby="card-label-4">
                        <ion-icon name="repeat-outline"></ion-icon>
                      </button>

                      <div class="card-action-tooltip" id="card-label-4">Compare</div>
                    </li>

                  </ul>
                </figure>

                <div class="card-content">

                  <div class="card-cat">
                    <a href="#" class="card-cat-link">Men</a> /
                    <a href="#" class="card-cat-link">Women</a>
                  </div>

                  <h3 class="h3 card-title">
                    <a href="#">Nike Air Max 270 SE</a>
                  </h3>

                  <data class="card-price" value="120.85">₹ 120.85</data>

                </div>

              </div>
            </li>

            <li class="product-item">
              <div class="product-card" tabindex="0">

                <figure class="card-banner">
                  <img src="./assets/images/product-6.jpg" width="312" height="350" loading="lazy"
                    alt="Adidas Sneakers Shoes" class="image-contain">

                  <ul class="card-action-list">

                    <li class="card-action-item">
                      <button class="card-action-btn" aria-labelledby="card-label-1">
                        <ion-icon name="cart-outline"></ion-icon>
                      </button>

                      <div class="card-action-tooltip" id="card-label-1">Add to Cart</div>
                    </li>

                    <li class="card-action-item">
                      <button class="card-action-btn" aria-labelledby="card-label-2">
                        <ion-icon name="heart-outline"></ion-icon>
                      </button>

                      <div class="card-action-tooltip" id="card-label-2">Add to Whishlist</div>
                    </li>

                    <li class="card-action-item">
                      <button class="card-action-btn" aria-labelledby="card-label-3">
                        <ion-icon name="eye-outline"></ion-icon>
                      </button>

                      <div class="card-action-tooltip" id="card-label-3">Quick View</div>
                    </li>

                    <li class="card-action-item">
                      <button class="card-action-btn" aria-labelledby="card-label-4">
                        <ion-icon name="repeat-outline"></ion-icon>
                      </button>

                      <div class="card-action-tooltip" id="card-label-4">Compare</div>
                    </li>

                  </ul>
                </figure>

                <div class="card-content">

                  <div class="card-cat">
                    <a href="#" class="card-cat-link">Men</a> /
                    <a href="#" class="card-cat-link">Women</a>
                  </div>

                  <h3 class="h3 card-title">
                    <a href="#">Adidas Sneakers Shoes</a>
                  </h3>

                  <data class="card-price" value="100.85">₹ 100.85</data>

                </div>

              </div>
            </li>

            <li class="product-item">
              <div class="product-card" tabindex="0">

                <figure class="card-banner">
                  <img src="./assets/images/product-7.jpg" width="312" height="350" loading="lazy"
                    alt="Nike Basketball shoes" class="image-contain">

                  <ul class="card-action-list">

                    <li class="card-action-item">
                      <button class="card-action-btn" aria-labelledby="card-label-1">
                        <ion-icon name="cart-outline"></ion-icon>
                      </button>

                      <div class="card-action-tooltip" id="card-label-1">Add to Cart</div>
                    </li>

                    <li class="card-action-item">
                      <button class="card-action-btn" aria-labelledby="card-label-2">
                        <ion-icon name="heart-outline"></ion-icon>
                      </button>

                      <div class="card-action-tooltip" id="card-label-2">Add to Whishlist</div>
                    </li>

                    <li class="card-action-item">
                      <button class="card-action-btn" aria-labelledby="card-label-3">
                        <ion-icon name="eye-outline"></ion-icon>
                      </button>

                      <div class="card-action-tooltip" id="card-label-3">Quick View</div>
                    </li>

                    <li class="card-action-item">
                      <button class="card-action-btn" aria-labelledby="card-label-4">
                        <ion-icon name="repeat-outline"></ion-icon>
                      </button>

                      <div class="card-action-tooltip" id="card-label-4">Compare</div>
                    </li>

                  </ul>
                </figure>

                <div class="card-content">

                  <div class="card-cat">
                    <a href="#" class="card-cat-link">Men</a> /
                    <a href="#" class="card-cat-link">Sports</a>
                  </div>

                  <h3 class="h3 card-title">
                    <a href="#">Nike Basketball shoes</a>
                  </h3>

                  <data class="card-price" value="120.85">₹ 120.85</data>

                </div>

              </div>
            </li>

            <li class="product-item">
              <div class="product-card" tabindex="0">

                <figure class="card-banner">
                  <img src="./assets/images/product-8.jpg" width="312" height="350" loading="lazy"
                    alt="Simple Fabric Shoe" class="image-contain">

                  <ul class="card-action-list">

                    <li class="card-action-item">
                      <button class="card-action-btn" aria-labelledby="card-label-1">
                        <ion-icon name="cart-outline"></ion-icon>
                      </button>

                      <div class="card-action-tooltip" id="card-label-1">Add to Cart</div>
                    </li>

                    <li class="card-action-item">
                      <button class="card-action-btn" aria-labelledby="card-label-2">
                        <ion-icon name="heart-outline"></ion-icon>
                      </button>

                      <div class="card-action-tooltip" id="card-label-2">Add to Whishlist</div>
                    </li>

                    <li class="card-action-item">
                      <button class="card-action-btn" aria-labelledby="card-label-3">
                        <ion-icon name="eye-outline"></ion-icon>
                      </button>

                      <div class="card-action-tooltip" id="card-label-3">Quick View</div>
                    </li>

                    <li class="card-action-item">
                      <button class="card-action-btn" aria-labelledby="card-label-4">
                        <ion-icon name="repeat-outline"></ion-icon>
                      </button>

                      <div class="card-action-tooltip" id="card-label-4">Compare</div>
                    </li>

                  </ul>
                </figure>

                <div class="card-content">

                  <div class="card-cat">
                    <a href="#" class="card-cat-link">Men</a> /
                    <a href="#" class="card-cat-link">Women</a>
                  </div>

                  <h3 class="h3 card-title">
                    <a href="#">Simple Fabric Shoe</a>
                  </h3>

                  <data class="card-price" value="100.85">₹ 100.85</data>

                </div>

              </div>
            </li>

          </ul>

        </div>
      </section>

      <section class="section cta">
        <div class="container">

          <ul class="cta-list">

            <li>
              <div class="cta-card" style="background-image: url('./assets/images/cta-1.jpg')">
                <p class="card-subtitle">Adidas Shoes</p>

                <h3 class="h2 card-title">The Summer Sale Off 50%</h3>

                <a href="#" class="btn btn-link">
                  <span>Shop Now</span>

                  <ion-icon name="arrow-forward-outline" aria-hidden="true"></ion-icon>
                </a>
              </div>
            </li>

            <li>
              <div class="cta-card" style="background-image: url('./assets/images/cta-2.jpg')">
                <p class="card-subtitle">Nike Shoes</p>

                <h3 class="h2 card-title">Makes Yourself Keep Sporty</h3>

                <a href="#" class="btn btn-link">
                  <span>Shop Now</span>

                  <ion-icon name="arrow-forward-outline" aria-hidden="true"></ion-icon>
                </a>
              </div>
            </li>

          </ul>

        </div>
      </section>

      <section class="section special">
        <div class="container">

          <div class="special-banner" style="background-image: url('./assets/images/special-banner.jpg')">
            <h2 class="h3 banner-title">New Trend Edition</h2>

            <a href="#" class="btn btn-link">
              <span>Explore All</span>

              <ion-icon name="arrow-forward-outline" aria-hidden="true"></ion-icon>
            </a>
          </div>

          <div class="special-product">

            <h2 class="h2 section-title">
              <span class="text">Nike Special</span>

              <span class="line"></span>
            </h2>

            <ul class="has-scrollbar">

              <li class="product-item">
                <div class="product-card" tabindex="0">

                  <figure class="card-banner">
                    <img src="./assets/images/product-1.jpg" width="312" height="350" loading="lazy"
                      alt="Running Sneaker Shoes" class="image-contain">

                    <div class="card-badge">New</div>

                    <ul class="card-action-list">

                      <li class="card-action-item">
                        <button class="card-action-btn" aria-labelledby="card-label-1">
                          <ion-icon name="cart-outline"></ion-icon>
                        </button>

                        <div class="card-action-tooltip" id="card-label-1">Add to Cart</div>
                      </li>

                      <li class="card-action-item">
                        <button class="card-action-btn" aria-labelledby="card-label-2">
                          <ion-icon name="heart-outline"></ion-icon>
                        </button>

                        <div class="card-action-tooltip" id="card-label-2">Add to Whishlist</div>
                      </li>

                      <li class="card-action-item">
                        <button class="card-action-btn" aria-labelledby="card-label-3">
                          <ion-icon name="eye-outline"></ion-icon>
                        </button>

                        <div class="card-action-tooltip" id="card-label-3">Quick View</div>
                      </li>

                      <li class="card-action-item">
                        <button class="card-action-btn" aria-labelledby="card-label-4">
                          <ion-icon name="repeat-outline"></ion-icon>
                        </button>

                        <div class="card-action-tooltip" id="card-label-4">Compare</div>
                      </li>

                    </ul>
                  </figure>

                  <div class="card-content">

                    <div class="card-cat">
                      <a href="#" class="card-cat-link">Men</a> /
                      <a href="#" class="card-cat-link">Women</a>
                    </div>

                    <h3 class="h3 card-title">
                      <a href="#">Running Sneaker Shoes</a>
                    </h3>

                    <data class="card-price" value="180.85">₹ 180.85</data>

                  </div>

                </div>
              </li>

              <li class="product-item">
                <div class="product-card" tabindex="0">

                  <figure class="card-banner">
                    <img src="./assets/images/product-2.jpg" width="312" height="350" loading="lazy"
                      alt="Leather Mens Slipper" class="image-contain">

                    <ul class="card-action-list">

                      <li class="card-action-item">
                        <button class="card-action-btn" aria-labelledby="card-label-1">
                          <ion-icon name="cart-outline"></ion-icon>
                        </button>

                        <div class="card-action-tooltip" id="card-label-1">Add to Cart</div>
                      </li>

                      <li class="card-action-item">
                        <button class="card-action-btn" aria-labelledby="card-label-2">
                          <ion-icon name="heart-outline"></ion-icon>
                        </button>

                        <div class="card-action-tooltip" id="card-label-2">Add to Whishlist</div>
                      </li>

                      <li class="card-action-item">
                        <button class="card-action-btn" aria-labelledby="card-label-3">
                          <ion-icon name="eye-outline"></ion-icon>
                        </button>

                        <div class="card-action-tooltip" id="card-label-3">Quick View</div>
                      </li>

                      <li class="card-action-item">
                        <button class="card-action-btn" aria-labelledby="card-label-4">
                          <ion-icon name="repeat-outline"></ion-icon>
                        </button>

                        <div class="card-action-tooltip" id="card-label-4">Compare</div>
                      </li>

                    </ul>
                  </figure>

                  <div class="card-content">

                    <div class="card-cat">
                      <a href="#" class="card-cat-link">Men</a> /
                      <a href="#" class="card-cat-link">Sports</a>
                    </div>

                    <h3 class="h3 card-title">
                      <a href="#">Leather Mens Slipper</a>
                    </h3>

                    <data class="card-price" value="190.85">₹ 190.85</data>

                  </div>

                </div>
              </li>

              <li class="product-item">
                <div class="product-card" tabindex="0">

                  <figure class="card-banner">
                    <img src="./assets/images/product-3.jpg" width="312" height="350" loading="lazy"
                      alt="Simple Fabric Shoe" class="image-contain">

                    <div class="card-badge">New</div>

                    <ul class="card-action-list">

                      <li class="card-action-item">
                        <button class="card-action-btn" aria-labelledby="card-label-1">
                          <ion-icon name="cart-outline"></ion-icon>
                        </button>

                        <div class="card-action-tooltip" id="card-label-1">Add to Cart</div>
                      </li>

                      <li class="card-action-item">
                        <button class="card-action-btn" aria-labelledby="card-label-2">
                          <ion-icon name="heart-outline"></ion-icon>
                        </button>

                        <div class="card-action-tooltip" id="card-label-2">Add to Whishlist</div>
                      </li>

                      <li class="card-action-item">
                        <button class="card-action-btn" aria-labelledby="card-label-3">
                          <ion-icon name="eye-outline"></ion-icon>
                        </button>

                        <div class="card-action-tooltip" id="card-label-3">Quick View</div>
                      </li>

                      <li class="card-action-item">
                        <button class="card-action-btn" aria-labelledby="card-label-4">
                          <ion-icon name="repeat-outline"></ion-icon>
                        </button>

                        <div class="card-action-tooltip" id="card-label-4">Compare</div>
                      </li>

                    </ul>
                  </figure>

                  <div class="card-content">

                    <div class="card-cat">
                      <a href="#" class="card-cat-link">Men</a> /
                      <a href="#" class="card-cat-link">Women</a>
                    </div>

                    <h3 class="h3 card-title">
                      <a href="#">Simple Fabric Shoe</a>
                    </h3>

                    <data class="card-price" value="160.85">₹ 160.85</data>

                  </div>

                </div>
              </li>

              <li class="product-item">
                <div class="product-card" tabindex="0">

                  <figure class="card-banner">
                    <img src="./assets/images/product-4.jpg" width="312" height="350" loading="lazy"
                      alt="Air Jordan 7 Retro " class="image-contain">

                    <div class="card-badge"> -25%</div>

                    <ul class="card-action-list">

                      <li class="card-action-item">
                        <button class="card-action-btn" aria-labelledby="card-label-1">
                          <ion-icon name="cart-outline"></ion-icon>
                        </button>

                        <div class="card-action-tooltip" id="card-label-1">Add to Cart</div>
                      </li>

                      <li class="card-action-item">
                        <button class="card-action-btn" aria-labelledby="card-label-2">
                          <ion-icon name="heart-outline"></ion-icon>
                        </button>

                        <div class="card-action-tooltip" id="card-label-2">Add to Whishlist</div>
                      </li>

                      <li class="card-action-item">
                        <button class="card-action-btn" aria-labelledby="card-label-3">
                          <ion-icon name="eye-outline"></ion-icon>
                        </button>

                        <div class="card-action-tooltip" id="card-label-3">Quick View</div>
                      </li>

                      <li class="card-action-item">
                        <button class="card-action-btn" aria-labelledby="card-label-4">
                          <ion-icon name="repeat-outline"></ion-icon>
                        </button>

                        <div class="card-action-tooltip" id="card-label-4">Compare</div>
                      </li>

                    </ul>
                  </figure>

                  <div class="card-content">

                    <div class="card-cat">
                      <a href="#" class="card-cat-link">Men</a> /
                      <a href="#" class="card-cat-link">Sports</a>
                    </div>

                    <h3 class="h3 card-title">
                      <a href="#">Air Jordan 7 Retro </a>
                    </h3>

                    <data class="card-price" value="170.85">₹ 170.85 <del>₹ 200.21</del></data>

                  </div>

                </div>
              </li>

            </ul>

          </div>

        </div>
      </section>

      <section class="section service">
        <div class="container">
          <ul class="service-list">
            <li class="service-item">
              <div class="service-card">

                <div class="card-icon">
                  <img src="./assets/images/service-1.png" width="53" height="28" loading="lazy" alt="Service icon">
                </div>

                <div>
                  <h3 class="h4 card-title">Free Shiping</h3>

                  <p class="card-text">
                    All orders over (minimum) <span>₹ 200</span>
                  </p>
                </div>

              </div>
            </li>

            <li class="service-item">
              <div class="service-card">

                <div class="card-icon">
                  <img src="./assets/images/service-2.png" width="43" height="35" loading="lazy" alt="Service icon">
                </div>

                <div>
                  <h3 class="h4 card-title">Quick Payment</h3>

                  <p class="card-text">
                    100% secure payment
                  </p>
                </div>

              </div>
            </li>

            <li class="service-item">
              <div class="service-card">

                <div class="card-icon">
                  <img src="./assets/images/service-3.png" width="40" height="40" loading="lazy" alt="Service icon">
                </div>

                <div>
                  <h3 class="h4 card-title">Free Returns</h3>

                  <p class="card-text">
                    Money back in 07 days
                  </p>
                </div>

              </div>
            </li>

            <li class="service-item">
              <div class="service-card">

                <div class="card-icon">
                  <img src="./assets/images/service-4.png" width="40" height="40" loading="lazy" alt="Service icon">
                </div>

                <div>
                  <h3 class="h4 card-title">24/7 Support</h3>

                  <p class="card-text">
                    Get Quick Support
                  </p>
                </div>
              </div>
            </li>
          </ul>
        </div>
      </section>

      <section class="section insta-post">
        <ul class="insta-post-list has-scrollbar">
          <li class="insta-post-item">
            <img src="./assets/images/insta-1.jpg" width="100" height="100" loading="lazy" alt="Instagram post"
              class="insta-post-banner image-contain">

            <a href="#" class="insta-post-link">
              <ion-icon name="logo-instagram"></ion-icon>
            </a>
          </li>

          <li class="insta-post-item">
            <img src="./assets/images/insta-2.jpg" width="100" height="100" loading="lazy" alt="Instagram post"
              class="insta-post-banner image-contain">

            <a href="#" class="insta-post-link">
              <ion-icon name="logo-instagram"></ion-icon>
            </a>
          </li>

          <li class="insta-post-item">
            <img src="./assets/images/insta-3.jpg" width="100" height="100" loading="lazy" alt="Instagram post"
              class="insta-post-banner image-contain">

            <a href="#" class="insta-post-link">
              <ion-icon name="logo-instagram"></ion-icon>
            </a>
          </li>

          <li class="insta-post-item">
            <img src="./assets/images/insta-4.jpg" width="100" height="100" loading="lazy" alt="Instagram post"
              class="insta-post-banner image-contain">

            <a href="#" class="insta-post-link">
              <ion-icon name="logo-instagram"></ion-icon>
            </a>
          </li>

          <li class="insta-post-item">
            <img src="./assets/images/insta-5.jpg" width="100" height="100" loading="lazy" alt="Instagram post"
              class="insta-post-banner image-contain">

            <a href="#" class="insta-post-link">
              <ion-icon name="logo-instagram"></ion-icon>
            </a>
          </li>

          <li class="insta-post-item">
            <img src="./assets/images/insta-6.jpg" width="100" height="100" loading="lazy" alt="Instagram post"
              class="insta-post-banner image-contain">

            <a href="#" class="insta-post-link">
              <ion-icon name="logo-instagram"></ion-icon>
            </a>
          </li>

          <li class="insta-post-item">
            <img src="./assets/images/insta-7.jpg" width="100" height="100" loading="lazy" alt="Instagram post"
              class="insta-post-banner image-contain">

            <a href="#" class="insta-post-link">
              <ion-icon name="logo-instagram"></ion-icon>
            </a>
          </li>

          <li class="insta-post-item">
            <img src="./assets/images/insta-8.jpg" width="100" height="100" loading="lazy" alt="Instagram post"
              class="insta-post-banner image-contain">

            <a href="#" class="insta-post-link">
              <ion-icon name="logo-instagram"></ion-icon>
            </a>
          </li>
        </ul>
      </section>
    </article>
  </main>

  <footer class="footer">

    <div class="footer-top section">
      <div class="container">

        <div class="footer-brand">

          <a href="#" class="logo">
            <img src="./assets/images/logo.png" width="250" height="50" alt="Pinaki FootWare logo">
          </a>

          <ul class="social-list">

            <li>
              <a href="#" class="social-link">
                <ion-icon name="logo-facebook"></ion-icon>
              </a>
            </li>

            <li>
              <a href="#" class="social-link">
                <ion-icon name="logo-twitter"></ion-icon>
              </a>
            </li>

            <li>
              <a href="#" class="social-link">
                <ion-icon name="logo-pinterest"></ion-icon>
              </a>
            </li>

            <li>
              <a href="#" class="social-link">
                <ion-icon name="logo-linkedin"></ion-icon>
              </a>
            </li>
          </ul>
        </div>

        <div class="footer-link-box">
          <ul class="footer-list">
            <li>
              <p class="footer-list-title">Contact Us</p>
            </li>

            <li>
              <address class="footer-link">
                <ion-icon name="location"></ion-icon>

                <span class="footer-link-text">
                  1/51, Mirpara Road, Bhattanagar, Liluah, Howrah - 711 203
                </span>
              </address>
            </li>

            <li>
              <a href="tel:+91 9339596197" class="footer-link">
                <ion-icon name="call"></ion-icon>

                <span class="footer-link-text">+91 9339596197</span>
              </a>
            </li>

            <li>
              <a href="mailto:pinakifootware@help.com" class="footer-link">
                <ion-icon name="mail"></ion-icon>

                <span class="footer-link-text">pinakifootware@help.com</span>
              </a>
            </li>
          </ul>

          <ul class="footer-list">
            <li>
              <p class="footer-list-title">My Account</p>
            </li>

            <li>
              <a href="#" class="footer-link">
                <ion-icon name="chevron-forward-outline"></ion-icon>

                <span class="footer-link-text">My Account</span>
              </a>
            </li>

            <li>
              <a href="#" class="footer-link">
                <ion-icon name="chevron-forward-outline"></ion-icon>

                <span class="footer-link-text">View Cart</span>
              </a>
            </li>

            <li>
              <a href="#" class="footer-link">
                <ion-icon name="chevron-forward-outline"></ion-icon>

                <span class="footer-link-text">Wishlist</span>
              </a>
            </li>

            <li>
              <a href="#" class="footer-link">
                <ion-icon name="chevron-forward-outline"></ion-icon>

                <span class="footer-link-text">Compare</span>
              </a>
            </li>

            <li>
              <a href="#" class="footer-link">
                <ion-icon name="chevron-forward-outline"></ion-icon>

                <span class="footer-link-text">New Products</span>
              </a>
            </li>

          </ul>

          <div class="footer-list">

            <p class="footer-list-title">Opening Time</p>

            <table class="footer-table">
              <tbody>

                <tr class="table-row">
                  <th class="table-head" scope="row">Mon:</th>

                  <td class="table-data">08 am - 10 pm</td>
                </tr>

                <tr class="table-row">
                  <th class="table-head" scope="row">Tue:</th>

                  <td class="table-data">08 am - 10 pm</td>
                </tr>
                
                <tr class="table-row">
                  <th class="table-head" scope="row">Wed:</th>

                  <td class="table-data">08 am - 07 pm</td>
                </tr>

                <tr class="table-row">
                  <th class="table-head" scope="row">Fri:</th>

                  <td class="table-data">07 am - 12 pm</td>
                </tr>

                <tr class="table-row">
                  <th class="table-head" scope="row">Sat:</th>

                  <td class="table-data">09 am - 08 pm </td>
                </tr>

                <tr class="table-row">
                  <th class="table-head" scope="row">Sun:</th>

                  <td class="table-data">Closed</td>
                </tr>

              </tbody>
            </table>
          </div>

          <div class="footer-list">
            <p class="footer-list-title">Newsletter</p>

            <p class="newsletter-text">
              Authoritatively alter 24/7 potentialities with error-free partnerships. The right shoes can make everything different.
            </p>

            <form action="" class="newsletter-form">
              <input type="email" name="email" required placeholder="Email Address" class="newsletter-input">

              <button type="submit" class="btn btn-primary">Subscribe</button>
            </form>
          </div>
        </div>
      </div>
    </div>

    <div class="footer-bottom">
      <div class="container">

        <p class="copyright">
          &copy; 2023 <a href="#" class="copyright-link">pinakifootwear</a>. All Rights Reserved
        </p>
      </div>
    </div>
  </footer>

  <a href="#top" class="go-top-btn" data-go-top>
    <ion-icon name="arrow-up-outline"></ion-icon>
  </a>

  <script src="./assets/js/script.js"></script>
  <script type="module" src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.esm.js"></script>
  <script nomodule src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.js"></script>

</body>
</html>

<INDEX2.HTML>

<!DOCTYPE html>
<html>
<head>
	<title>Pinaki FootWear</title>
	<meta charset="utf-8">
	<link href='https://unpkg.com/boxicons@2.0.7/css/boxicons.min.css' rel='stylesheet'>
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<link rel="stylesheet" type="text/css" href="style2.css">
    <link rel="shortcut icon" href="pinaki logo.jpg" type="image/svg+xml">
</head>
<body>

	<div class="navbar">
		<a href="#" class="logo">
			<img src="./assets/images/logo.png" width="250" height="50" alt="Pinaki FootWare logo">
		</a>
		<div class="navbar-right menu">
			<a href="#" class="active">New releases</a>
			<a href="#">Men</a>
			<a href="#">Women</a>
			<a href="#">Kids</a>
			<a href="#">About</a>
			<a href="#">Contacts</a>
		</div>
		<div class="navbar-right">
			<a href="#" class="cart">
				<i class="bx bx-cart-alt"></i>
				<span class="badge">2</span>
			</a>
		</div>
	</div>

	<div id="slider" class="slider">

		<div class="row fullheight slide">
			<div class="col-6 fullheight">

				<div class="product-info">
					<div class="info-wrapper">&nbsp;&nbsp;
						<div class="product-price left-to-right">
							<span>₹</span>230
						</div>
						<div class="product-name left-to-right">
							<h2>
								Nike ZoomX Vaporfly NEXT%
							</h2>
						</div>
						<div class="product-size left-to-right">
							<h3>SIZE</h3>
							<div class="size-wrapper">
								<div>35</div>
								<div>36</div>
								<div class="active">37</div>
								<div>38</div>
								<div>39</div>
								<div>40</div>
							</div>
						</div>
						<div class="product-color left-to-right">
							<h3>COLORS</h3>
							<div class="color-wrapper">
								<div class="active">
									<div class="bg-red"></div>
								</div>
								<div class="">
									<div class="bg-blue"></div>
								</div>
								<div class="">
									<div class="bg-white"></div>
								</div>
							</div>
						</div>
						<div class="product-description left-to-right">
							<p>
								The Nike ZoomX Vaporfly NEXT% clears your path to record-breaking speed with a lighter design and faster feel than before.
							</p>
						</div>
						<div class="button left-to-right">
							<button>
								Add to cart
							</button>
						</div>
					</div>
				</div>

			</div>
			<div class="col-6 fullheight img-col" style="background-image: linear-gradient(to top right, #e19e95, #fd835c)">

				<div class="product-img">
					<div class="img-wrapper right-to-left">
						<div class="bounce">
							<img src="assets/images/zoomx-vaporfly-next-running-shoe-4Q5jfG.png" alt="placeholder+image">
						</div>
					</div>
				</div>

				<div class="more-images">
					<div class="more-images-item bottom-up">
						<img src="assets/images/zoomx-vaporfly-next-running-shoe-4Q5jfG-1.jpg" alt="placeholder+image">
					</div>
					<div class="more-images-item bottom-up">
						<img src="assets/images/zoomx-vaporfly-next-running-shoe-4Q5jfG (1).jpg" alt="placeholder+image">
					</div>
					<div class="more-images-item bottom-up">
						<img src="assets/images/zoomx-vaporfly-next-running-shoe-4Q5jfG (3).jpg" alt="placeholder+image">
					</div>
					<div class="more-images-item bottom-up">
						<img src="assets/images/zoomx-vaporfly-next-running-shoe-4Q5jfG (4).jpg" alt="placeholder+image">
					</div>
				</div>

			</div>
		</div>

		<div class="row fullheight slide">
			<div class="col-6 fullheight">

				<div class="product-info">
					<div class="info-wrapper">
						<div class="product-price left-to-right">
							<span>₹</span>450
						</div>
						<div class="product-name left-to-right">
							<h2>
								Nike Zoom Fly 3
							</h2>
						</div>
						<div class="product-size left-to-right">
							<h3>SIZE</h3>
							<div class="size-wrapper">
								<div>35</div>
								<div>36</div>
								<div class="active">37</div>
								<div>38</div>
								<div>39</div>
								<div>40</div>
							</div>
						</div>
						<div class="product-color left-to-right">
							<h3>COLORS</h3>
							<div class="color-wrapper">
								<div class="active">
									<div class="bg-red"></div>
								</div>
								<div class="">
									<div class="bg-blue"></div>
								</div>
								<div class="">
									<div class="bg-white"></div>
								</div>
							</div>
						</div>
						<div class="product-description left-to-right">
							<p>
								The Nike Zoom Fly 3 clears your path to record-breaking speed with a lighter design and faster feel than before. 
							</p>
						</div>
						<div class="button left-to-right">
							<button>
								Add to cart
							</button>
						</div>
					</div>
				</div>

			</div>
			<div class="col-6 fullheight img-col" style="background-image: linear-gradient(to top right, #6b6d68, #629f2a)">

				<div class="product-img">
					<div class="img-wrapper right-to-left">
						<div class="bounce">
							<img src="assets/images/zoom-fly-3-mens-running-shoe-XhzpPH.png" alt="placeholder+image">
						</div>
					</div>
				</div>

				<div class="more-images">
					<div class="more-images-item bottom-up">
						<img src="assets/images/zoom-fly-3-mens-running-shoe-XhzpPH.jpg" alt="placeholder+image">
					</div>
					<div class="more-images-item bottom-up">
						<img src="assets/images/zoom-fly-3-mens-running-shoe-XhzpPH (1).jpg" alt="placeholder+image">
					</div>
					<div class="more-images-item bottom-up">
						<img src="assets/images/zoom-fly-3-mens-running-shoe-XhzpPH (2).jpg" alt="placeholder+image">
					</div>
					<div class="more-images-item bottom-up">
						<img src="assets/images/zoom-fly-3-mens-running-shoe-XhzpPH (3).jpg" alt="placeholder+image">
					</div>
				</div>

			</div>
		</div>

		<div class="row fullheight slide">
			<div class="col-6 fullheight">

				<div class="product-info">
					<div class="info-wrapper">
						<div class="product-price left-to-right">
							<span>₹</span>300
						</div>
						<div class="product-name left-to-right">
							<h2>
								Nike Air Max Alpha TR 3
							</h2>
						</div>
						<div class="product-size left-to-right">
							<h3>SIZE</h3>
							<div class="size-wrapper">
								<div>35</div>
								<div>36</div>
								<div class="active">37</div>
								<div>38</div>
								<div>39</div>
								<div>40</div>
							</div>
						</div>
						<div class="product-color left-to-right">
							<h3>COLORS</h3>
							<div class="color-wrapper">
								<div class="active">
									<div class="bg-red"></div>
								</div>
								<div class="">
									<div class="bg-blue"></div>
								</div>
								<div class="">
									<div class="bg-white"></div>
								</div>
							</div>
						</div>
						<div class="product-description left-to-right">
							<p>
								The Nike Air Max Alpha TR 3 clears your path to record-breaking speed with a lighter design and faster feel than before.
							</p>
						</div>
						<div class="button left-to-right">
							<button>
								Add to cart
							</button>
						</div>
					</div>
				</div>

			</div>
			<div class="col-6 fullheight img-col" style="background-image: linear-gradient(to top right, #cdcbd3, #171617)">

				<div class="product-img">
					<div class="img-wrapper right-to-left">
						<div class="bounce">
							<img src="assets/images/air-max-alpha-tr-3-mens-training-shoe-0C1CV7.png" alt="placeholder+image">
						</div>
					</div>
				</div>

				<div class="more-images">
					<div class="more-images-item bottom-up">
						<img src="assets/images/air-max-alpha-tr-3-mens-training-shoe-0C1CV7.jpg" alt="placeholder+image">
					</div>
					<div class="more-images-item bottom-up">
						<img src="assets/images/air-max-alpha-tr-3-mens-training-shoe-0C1CV7 (1).jpg" alt="placeholder+image">
					</div>
					<div class="more-images-item bottom-up">
						<img src="assets/images/air-max-alpha-tr-3-mens-training-shoe-0C1CV7 (2).jpg" alt="placeholder+image">
					</div>
					<div class="more-images-item bottom-up">
						<img src="assets/images/air-max-alpha-tr-3-mens-training-shoe-0C1CV7 (3).jpg" alt="placeholder+image">
					</div>
				</div>

			</div>
		</div>

		<div class="row fullheight slide">
			<div class="col-6 fullheight">

				<div class="product-info">
					<div class="info-wrapper">
						<div class="product-price left-to-right">
							<span>₹</span>290
						</div>
						<div class="product-name left-to-right">
							<h2>
								Nike Air Zoom SuperRep
							</h2>
						</div>
						<div class="product-size left-to-right">
							<h3>SIZE</h3>
							<div class="size-wrapper">
								<div>35</div>
								<div>36</div>
								<div class="active">37</div>
								<div>38</div>
								<div>39</div>
								<div>40</div>
							</div>
						</div>
						<div class="product-color left-to-right">
							<h3>COLORS</h3>
							<div class="color-wrapper">
								<div class="active">
									<div class="bg-red"></div>
								</div>
								<div class="">
									<div class="bg-blue"></div>
								</div>
								<div class="">
									<div class="bg-white"></div>
								</div>
							</div>
						</div>
						<div class="product-description left-to-right">
							<p>
								The Nike Air Zoom SuperRep clears your path to record-breaking speed with a lighter design and faster feel than before.
							</p>
						</div>
						<div class="button left-to-right">
							<button>
								Add to cart
							</button>
						</div>
					</div>
				</div>

			</div>
			<div class="col-6 fullheight img-col" style="background-image: linear-gradient(to top right, #32519a, #4967af)">

				<div class="product-img">
					<div class="img-wrapper right-to-left">
						<div class="bounce">
							<img src="assets/images/air-zoom-superrep-mens-hiit-class-shoe-ZWLnJW (1).png" alt="placeholder+image">
						</div>
					</div>
				</div>

				<div class="more-images">
					<div class="more-images-item bottom-up">
						<img src="assets/images/air-zoom-superrep-mens-hiit-class-shoe-ZWLnJW.jpg" alt="placeholder+image">
					</div>
					<div class="more-images-item bottom-up">
						<img src="assets/images/air-zoom-superrep-mens-hiit-class-shoe-ZWLnJW (4).jpg" alt="placeholder+image">
					</div>
					<div class="more-images-item bottom-up">
						<img src="assets/images/air-zoom-superrep-mens-hiit-class-shoe-ZWLnJW (3).jpg" alt="placeholder+image">
					</div>
					<div class="more-images-item bottom-up">
						<img src="assets/images/air-zoom-superrep-mens-hiit-class-shoe-ZWLnJW (2).jpg" alt="placeholder+image">
					</div>
				</div>

			</div>
		</div>

		<div id="slide-control" class="slide-control">
			<div class="slide-control-item">
				<img src="assets/images/zoomx-vaporfly-next-running-shoe-4Q5jfG.png" alt="placeholder+image">
			</div>
			<div class="slide-control-item">
				<img src="assets/images/zoom-fly-3-mens-running-shoe-XhzpPH.png" alt="placeholder+image">
			</div>
			<div class="slide-control-item">
				<img src="assets/images/air-max-alpha-tr-3-mens-training-shoe-0C1CV7.png" alt="placeholder+image">
			</div>
			<div class="slide-control-item">
				<img src="assets/images/air-zoom-superrep-mens-hiit-class-shoe-ZWLnJW (1).png" alt="placeholder+image">
			</div>
		</div>

	</div>

	<div id="modal" class="modal">
		<span id="modal-close" class="close">&times;</span>
		<img id="modal-content" class="modal-content">
		<div class="more-images">
			<div class="more-images-item">
				<img class="img-preview">
			</div>
			<div class="more-images-item">
				<img class="img-preview">
			</div>
			<div class="more-images-item">
				<img class="img-preview">
			</div>
			<div class="more-images-item">
				<img class="img-preview">
			</div>
		</div>
	</div>

	<script type="text/javascript" src="index2.js"></script>
</body>
</html>

<!--INDEX2.JS-->

let slideIndex = 0;

let slider = document.getElementById('slider')

let slides = slider.getElementsByClassName('slide')

let slideControl = document.getElementById('slide-control')

let slideControlItems = slideControl.getElementsByClassName('slide-control-item')


slider.style.marginTop = '-' + slideIndex + '00vh'

setTimeout(() => {
	slideControlItems[slideIndex].classList.add('active')
	slides[slideIndex].classList.add('active')
}, 500)


chooseProduct = (index) => {
	if (index === slideIndex) return

	slideIndex = index

	let currSlideControl = slideControl.querySelector('.slide-control-item.active')
	currSlideControl.classList.remove('active')

	let currSlide = slider.querySelector('.slide.active')
	currSlide.classList.remove('active')

	setTimeout(() => {
		slider.style.marginTop = '-' + slideIndex + '00vh'
		slideControlItems[slideIndex].classList.add('active')
		slides[slideIndex].classList.add('active')
	}, 1500)
	
}

Array.from(slideControlItems).forEach((el, index) => {
	el.onclick = function() {
		chooseProduct(index)
	}
})

let modal = document.getElementById('modal')

let closeBtn = document.getElementById('modal-close')

closeBtn.onclick = () => {
	modal.style.display = 'none'
}

let moreImages = document.getElementsByClassName('more-images-item')

let previewImages = document.getElementsByClassName('img-preview')

Array.from(moreImages).forEach((el) => {
	el.onclick = () => {
		let imgItems = el.parentNode.getElementsByTagName('img')

		Array.from(imgItems).forEach((item, index) => {
			previewImages[index].src = item.src
		})

		let img = el.querySelector('img')
		modal.style.display = 'block'

		let modalContent = modal.querySelector('.modal-content')
		modalContent.src = img.src

		let temp = modalContent.cloneNode(true)
		modalContent.parentNode.replaceChild(temp, modalContent)
	}
})

<!--STYLE2.CSS-->

:root {
	--red: #ff3838;
	--white: #ffffff;
	--black: #000000;

	--red-one: #CB356B;
	--red-two: #BD3F32;

	--green-one: #56ab2f;
	--green-two: #94d049;

	--black-one: #232526;
	--black-two: #70767b;

	--blue-one: #021B79;
	--blue-two: #0575E6;

	--silver: #bdc3c7;
}

@import url('https://fonts.googleapis.com/css2?family=Lato:wght@400;700;900&display=swap');

* {
	margin: 0;
	padding: 0;
	box-sizing: border-box;
	font-family: 'Lato', sans-serif;
}

.bg-red {
	background-color: var(--red);
}

.bg-white {
	background-color: var(--white);
}

.bg-black {
	background-color: var(--black);
}

.bg-blue {
	background-color: var(--blue-one);
}

.bg-green {
	background-color: var(--green-one);
}

body, html {
	margin: 0;
	padding: 0;
	height: 100%;
	width: 100%;
	overflow: hidden;
	background-image:url(assets/images/background.avif);
}

.row {
	display: flex;
	flex-wrap: wrap;
	flex-direction: row;
}

.row:after, .row:before {
	box-sizing: border-box;
}

.col-6 {
	width: 50%;
	position: relative;
}

.slider {
	overflow: hidden;
	height: 500%;
}

.fullheight {
	height: 100vh;
}

.product-img {
	position: absolute;
	top: 50%;
	left: 50%;
	transform: translate(-50%, -50%);
	width: 100%;
}

.img-wrapper img {
	height: auto;
	width: 80%;
	transform: rotate(-35deg);
}

.more-images {
	position: absolute;
	right: 90px;
	top: 50%;
}

.more-images-item {
	height: fit-content;
	border-radius: 15px;
	overflow: hidden;
	margin: 5px 0;
}

.more-images-item img {
	height: auto;
	width: 80px;
	border-radius: 15px;
	transition: 1s;
}

.more-images-item:hover img {
	transform: scale(1.5);
}

.more-images-item:hover {
	cursor: pointer;
}

.product-info {
	position: absolute;
	top: 50%;
	left: 50%;
	transform: translate(-50%, -50%);
	width: 100%;
	padding: 0 10%;
	color: var(--silver);
}

.info-wrapper {
	margin: auto;
	position: relative;
	text-align: right;
}

.product-name h2 {
	font-weight: 900;
	font-size: xxx-large;
	color: var(--black);
}

.product-price {
	font-weight: 900;
	font-size: xx-large;
	color: var(--black);
}

.product-price span {
	font-size: large;
	color: var(--black-two);
}

.product-size {
	margin: 20px 0;
}

.size-wrapper {
	display: flex;
	flex-flow: row-reverse;
	padding: 5px;
}

.size-wrapper div {
	font-weight: 900;
	margin: 5px;
	width: 50px;
	height: 50px;
	border-radius: 50%;
	padding: 13px;
	border: 2px solid var(--silver);
	color: var(--silver);
}

.size-wrapper div.active {
	border: 2px solid var(--black);
	color: var(--black);
}

.size-wrapper div:hover {
	border: 2px solid var(--black);
	color: var(--black);
	cursor: pointer;
}

.color-wrapper {
	display: flex;
	flex-flow: row-reverse;
	padding: 5px;
}

.color-wrapper > div {
	margin: 5px;
	width: 50px;
	height: 50px;
	border-radius: 50%;
	padding: 3px;
	border: 2px solid var(--silver);
	background-color: var(--silver);
}

.color-wrapper > div.active {
	border: 2px solid var(--black);
}

.color-wrapper > div:hover {
	cursor: pointer;
	border: 2px solid var(--black);
}

.color-wrapper > div >div {
	width: 40px;
	height: 40px;
	border-radius: 50%;
}

.product-description {
	margin: 60px 0;
	text-align: justify;
	font-weight: 600;
}

.button > button {
	font-weight: 900;
	font-size: x-large;
	padding: 15px 60px;
	border-radius: 30px;
	border: 2px solid var(--black);
	background-color: var(--white);
	color: var(--black);
	transition: .5s;
}

.button > button:hover {
	cursor: pointer;
	background-color: var(--black);
	color: var(--white);
}

.img-col {
	border-bottom-left-radius: 100%;
}

.slide-control {
	display: flex;
	padding: 5px;
	position: absolute;
	bottom: 0;
	left: 50%;
	transform: translateX(-50%);
}

.slide-control div {
	height: 50px;
	width: 50px;
	margin: 10px;
	transition: .5s;
}

.slide-control div:hover {
	cursor: pointer;
	transform: translateY(-30px);
	border-bottom: 2px solid var(--black);
}

.slide-control div img {
	height: auto;
	width: 100%;
	filter: grayscale(100%);
	transform: rotate(-45deg);
}

.slide-control div:hover img {
	filter: unset;
}

.slide-control div.active img {
	filter: unset;
}

.slide-control div.active {
	border-bottom: 2px solid var(--black);
}

.modal {
	display: none;
	position: fixed;
	z-index: 100;
	padding-top: 100px;
	left: 0;
	top: 0;
	width: 100%;
	height: 100%;
	overflow: auto;
	background-color: rgb(0,0,0);
	background-color: rgba(0,0,0,0.9);
}

.modal-content {
	margin: auto;
	display: block;
	width: 80%;
	max-width: 700px;
}

.modal-content {
	animation-name: zoom;
	animation-duration: .6s;
}

@keyframes zoom {
	from {
		transform: scale(0);
	} to {
		transform: scale(1);
	}
}

.close {
	position: absolute;
	top: 15px;
	right: 35px;
	color: var(--white);
	font-size: 40px;
	font-weight: 900;
	transition: .3s;
}

.close:hover, .close:focus {
	color: var(--silver);
	text-decoration: none;
	cursor: pointer;
}

.navbar {
	background-color: transparent;
	padding: 10px 90px;
	position: fixed;
	top: 0;
	left: 0;
	right: 0;
	z-index: 99;
	display: flex;
}

.navbar a {
	float: left;
	color: var(--white);
	text-decoration: none;
	font-size: 14px;
	font-weight: 900;
	padding:12px;
	text-transform: uppercase;
}

.navbar .logo {
	font-size: 30px;
	flex: 1;
	color: var(--black);
}

.navbar-right a:hover {
	color: var(--black);
	border-bottom: 2px solid var(--black);
}

.navbar-right a.active {
	color: var(--black);
	border-bottom: 2px solid var(--black);
}

.navbar-right a {
	transition: .5s;
}

.cart {
	position: relative;
}

.cart i {
	font-size: x-large;
}

.badge {
	position: absolute;
	top: 0;
	right: 1px;
	font-size: 12px;
	background-color: var(--red);
	width: 20px;
	height: 20px;
	padding: 2px;
	text-align: center;
	justify-content: center;
	border-radius: 50%;
}



.right-to-left {
	transition: 1s;
	transform: translateX(100%);
}

.active .right-to-left {
	transform: translateX(0);
}

.bottom-up {
	transition: 1s;
	transform: translateY(100vh);
}

.active .bottom-up {
	transform: translateY(0);
}

.left-to-right {
	transition: 1s;
	transform: translateX(-150%);
}

.active .left-to-right {
	transition: 1s;
	transform: translateX(0);
}

.more-images-item:nth-child(1) {
	transition-delay: .2s;
}

.more-images-item:nth-child(2) {
	transition-delay: .4s;
}

.more-images-item:nth-child(3) {
	transition-delay: .6s;
}

.more-images-item:nth-child(4) {
	transition-delay: .8s;
}

.info-wrapper > div:nth-child(1) {
	transition-delay: .2s;
}

.info-wrapper > div:nth-child(2) {
	transition-delay: .4s;
}

.info-wrapper > div:nth-child(3) {
	transition-delay: .6s;
}

.info-wrapper > div:nth-child(4) {
	transition-delay: .8s;
}

.info-wrapper > div:nth-child(5) {
	transition-delay: 1s;
}

.info-wrapper > div:nth-child(6) {
	transition-delay: 1.2s;
}

.bounce {
	animation-name: bounce;
	animation-timing-function: ease;
	animation-iteration-count: infinite;
	animation-duration: 3s;
}

@keyframes bounce {
	0% {
		transform: translateY(0);
	} 50% {
		transform: translateY(-50px);
	} 100% {
		transform: translateY(0);
	}
}
