<template>
  <div id="app">

    <b-navbar toggleable="sm" type="light" variant="light">

      <div class="container">

        <b-navbar-brand href="#">Магазин</b-navbar-brand>

        <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

        <b-collapse id="nav-collapse" is-nav>
          <b-navbar-nav>
            <b-nav-item href="#">Ссылка</b-nav-item>
            <b-nav-item href="#" disabled>Отключено</b-nav-item>
          </b-navbar-nav>

        </b-collapse>

      </div>

    </b-navbar>

    <div class="container">
      <b-row>
        <b-col cols="2">меню</b-col>
        <b-col cols="10">
          <b-jumbotron header="Мой гаражик" lead="Лучший Магазин для купли продажи вашего авто с помощью авито доставки">
            <p>Для получения дополнительной информации посетите веб-сайт</p>
            <b-button variant="primary" href="#">https://www.avito.ru/dostavka</b-button>
          </b-jumbotron>
          <hr>


          <b-card title="Бэъа"
            img-src="https://avatars.mds.yandex.net/get-autoru-reviews/1387785/Qa1HGuJ9G1w9NQ6v2BXCMLQuo17fmEPKr/1200x900"
            img-alt="Изображение" img-top tag="article" style="max-width: 20rem;" class="mb-2">
            <b-card-text>
              МОЯ ТАЧКА САМАЯ ЛУЧШАЯ НА ВСЕМ СЕЛЕ ВСЕГО ЗА 100 рублей БЕЛОРУССКИХ пососу ваш бензин.
            </b-card-text>

            <b-button href="#" variant="primary">КУПИЛ БЫСТРО</b-button>

          </b-card>
          <b-card title="Заголовок карточки"
            img-src="https://avatars.mds.yandex.net/get-autoru-reviews/1387785/Qa1HGuJ9G1w9NQ6v2BXCMLQuo17fmEPKr/1200x900"
            img-alt="Изображение" img-top tag="article" style="max-width: 20rem;" class="mb-2">
            <b-card-text>
              МОЯ ТАЧКА САМАЯ ЛУЧШАЯ НА ВСЕМ СЕЛЕ ВСЕГО ЗА 100 рублей БЕЛОРУССКИХ пососу ваш бензин.
            </b-card-text>

            <b-button href="#" variant="primary">КУПИЛ БЫСТРО</b-button>

          </b-card>

        </b-col>
      </b-row>


      <div class="album py-5 bg-light">
        <div class="container">
          <ol class="breadcrumb">
            <li aria-current="page" class="breadcrumb-item active">
              <b>all</b>
            </li>
            <li aria-current="page" class="breadcrumb-item active">
              <a href="#">electronics</a>
            </li>
            <li aria-current="page" class="breadcrumb-item active">
              <a href="#">jewelery</a>
            </li>
            <li aria-current="page" class="breadcrumb-item active">
              <a href="#">men's clothing</a>
            </li>
            <li aria-current="page" class="breadcrumb-item active">
              <a href="#">women's clothing</a>
            </li>
          </ol>
          <div class="row row-cols-1 row-cols-sm-2 row-cols-md-3 g-3">
            <div class="col">
              <div class="card shadow-sm" style="padding: 12px;">
                <img src="https://fakestoreapi.com/img/81fPKd-2AYL._AC_SL1500_.jpg"
                  class="bd-placeholder-img card-img-top">
                <div class="card-body">
                  <h5 class="card-title">Fjallraven - Foldsack No. 1 Backpack, Fits 15 Laptops</h5>
                  <h3 class="card-title">7696.5 ₽</h3>
                  <p class="card-text">Your perfect pack for everyday use and walks in the forest. Stash your laptop (up
                    to 15 inches) in the padded sleeve, your everyday</p>
                  <div class="d-flex justify-content-between align-items-center">
                    <div class="btn-group">
                      <button type="button" class="btn btn-sm btn-outline-secondary">Заказать

                      </button>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div class="col">
              <div class="card shadow-sm" style="padding: 12px;">
                <img src="https://fakestoreapi.com/img/71-3HjGNDUL._AC_SY879._SX._UX._SY._UY_.jpg"
                  class="bd-placeholder-img card-img-top">
                <div class="card-body">
                  <h5 class="card-title">Mens Casual Premium Slim Fit T-Shirts </h5>
                  <h3 class="card-title">1561 ₽</h3>
                  <p class="card-text">Slim-fitting style, contrast raglan long sleeve, three-button henley placket, light
                    weight &amp; soft fabric for breathable and comfortable wearing.
                    And Solid stitched shirts with round neck made for durability and a great fit for casual fashion wear
                    and diehard baseball fans.
                    The Henley style round neckline includes a three-button placket.</p>
                  <div class="d-flex justify-content-between align-items-center">
                    <div class="btn-group">
                      <button type="button" class="btn btn-sm btn-outline-secondary">
                        Заказать</button>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div class="col">
              <div class="card shadow-sm" style="padding: 12px;">
                <img src="https://fakestoreapi.com/img/71li-ujtlUL._AC_UX679_.jpg"
                class="bd-placeholder-img card-img-top">
              <div class="card-body">
                <h5 class="card-title">Mens Cotton Jacket</h5>
                <h3 class="card-title">3919.3 ₽</h3>
                <p class="card-text">great outerwear jackets for Spring/Autumn/Winter, suitable for many occasions, such
                  as working, hiking, camping, mountain/rock climbing, cycling, traveling or other outdoors. Good gift
                  choice for you or your family member. A warm hearted love to Father, husband or son in this
                  thanksgiving or Christmas Day.</p>
                <div class="d-flex justify-content-between align-items-center">
                  <div class="btn-group"><button type="button"
                      class="btn btn-sm btn-outline-secondary">Заказать</button></div>
                </div>
              </div>
            </div>
          </div>
          <div class="col">
            <div class="card shadow-sm" style="padding: 12px;"><img
                src="https://fakestoreapi.com/img/71YXzeOuslL._AC_UY879_.jpg" class="bd-placeholder-img card-img-top">
              <div class="card-body">
                <h5 class="card-title">Mens Casual Slim Fit</h5>
                <h3 class="card-title">1119.3 ₽</h3>
                <p class="card-text">The color could be slightly different between on the screen and in practice. /
                  Please note that body builds vary by person, therefore, detailed size information should be reviewed
                  below on the product description.</p>
                <div class="d-flex justify-content-between align-items-center">
                  <div class="btn-group"><button type="button"
                      class="btn btn-sm btn-outline-secondary">Заказать</button></div>
                </div>
              </div>
            </div>
          </div>
          <div class="col">
            <div class="card shadow-sm" style="padding: 12px;"><img
                src="https://fakestoreapi.com/img/71pWzhdJNwL._AC_UL640_QL65_ML3_.jpg"
                class="bd-placeholder-img card-img-top">
              <div class="card-body">
                <h5 class="card-title">John Hardy Women's Legends Naga Gold &amp; Silver Dragon Station Chain Bracelet
                </h5>
                <h3 class="card-title">48650 ₽</h3>
                <p class="card-text">From our Legends Collection, the Naga was inspired by the mythical water dragon
                  that protects the ocean's pearl. Wear facing inward to be bestowed with love and abundance, or outward
                  for protection.</p>
                <div class="d-flex justify-content-between align-items-center">
                  <div class="btn-group"><button type="button"
                      class="btn btn-sm btn-outline-secondary">Заказать</button></div>
                </div>
              </div>
            </div>
          </div>
          <div class="col">
            <div class="card shadow-sm" style="padding: 12px;"><img
                src="https://fakestoreapi.com/img/61sbMiUnoGL._AC_UL640_QL65_ML3_.jpg"
                class="bd-placeholder-img card-img-top">
              <div class="card-body">
                <h5 class="card-title">Solid Gold Petite Micropave </h5>
                <h3 class="card-title">11760 ₽</h3>
                <p class="card-text">Satisfaction Guaranteed. Return or exchange any order within 30 days.Designed and
                  sold by Hafeez Center in the United States. Satisfaction Guaranteed. Return or exchange any order
                  within 30 days.</p>
                <div class="d-flex justify-content-between align-items-center">
                  <div class="btn-group"><button type="button"
                      class="btn btn-sm btn-outline-secondary">Заказать</button></div>
                </div>
              </div>
            </div>
          </div>
          <div class="col">
            <div class="card shadow-sm" style="padding: 12px;"><img
                src="https://fakestoreapi.com/img/71YAIFU48IL._AC_UL640_QL65_ML3_.jpg"
                class="bd-placeholder-img card-img-top">
              <div class="card-body">
                <h5 class="card-title">White Gold Plated Princess</h5>
                <h3 class="card-title">699.3000000000001 ₽</h3>
                <p class="card-text">Classic Created Wedding Engagement Solitaire Diamond Promise Ring for Her. Gifts to
                  spoil your love more for Engagement, Wedding, Anniversary, Valentine's Day...</p>
                <div class="d-flex justify-content-between align-items-center">
                  <div class="btn-group"><button type="button"
                      class="btn btn-sm btn-outline-secondary">Заказать</button></div>
                </div>
              </div>
            </div>
          </div>
          <div class="col">
            <div class="card shadow-sm" style="padding: 12px;"><img
                src="https://fakestoreapi.com/img/51UDEzMJVpL._AC_UL640_QL65_ML3_.jpg"
                class="bd-placeholder-img card-img-top">
              <div class="card-body">
                <h5 class="card-title">Pierced Owl Rose Gold Plated Stainless Steel Double</h5>
                <h3 class="card-title">769.3000000000001 ₽</h3>
                <p class="card-text">Rose Gold Plated Double Flared Tunnel Plug Earrings. Made of 316L Stainless Steel
                </p>
                <div class="d-flex justify-content-between align-items-center">
                  <div class="btn-group"><button type="button"
                      class="btn btn-sm btn-outline-secondary">Заказать</button></div>
                </div>
              </div>
            </div>
          </div>
          <div class="col">
            <div class="card shadow-sm" style="padding: 12px;"><img
                src="https://fakestoreapi.com/img/61IBBVJvSDL._AC_SY879_.jpg" class="bd-placeholder-img card-img-top">
              <div class="card-body">
                <h5 class="card-title">WD 2TB Elements Portable External Hard Drive - USB 3.0 </h5>
                <h3 class="card-title">4480 ₽</h3>
                <p class="card-text">USB 3.0 and USB 2.0 Compatibility Fast data transfers Improve PC Performance High
                  Capacity; Compatibility Formatted NTFS for Windows 10, Windows 8.1, Windows 7; Reformatting may be
                  required for other operating systems; Compatibility may vary depending on user’s hardware
                  configuration and operating system</p>
                <div class="d-flex justify-content-between align-items-center">
                  <div class="btn-group"><button type="button"
                      class="btn btn-sm btn-outline-secondary">Заказать</button></div>
                </div>
              </div>
            </div>
          </div>
          <div class="col">
            <div class="card shadow-sm" style="padding: 12px;"><img
                src="https://fakestoreapi.com/img/61U7T1koQqL._AC_SX679_.jpg" class="bd-placeholder-img card-img-top">
              <div class="card-body">
                <h5 class="card-title">SanDisk SSD PLUS 1TB Internal SSD - SATA III 6 Gb/s</h5>
                <h3 class="card-title">7630 ₽</h3>
                <p class="card-text">Easy upgrade for faster boot up, shutdown, application load and response (As
                  compared to 5400 RPM SATA 2.5” hard drive; Based on published specifications and internal benchmarking
                  tests using PCMark vantage scores) Boosts burst write performance, making it ideal for typical PC
                  workloads The perfect balance of performance and reliability Read/write speeds of up to
                  535MB/s/450MB/s (Based on internal testing; Performance may vary depending upon drive capacity, host
                  device, OS and application.)</p>
                <div class="d-flex justify-content-between align-items-center">
                  <div class="btn-group"><button type="button"
                      class="btn btn-sm btn-outline-secondary">Заказать</button></div>
                </div>
              </div>
            </div>
          </div>
          <div class="col">
            <div class="card shadow-sm" style="padding: 12px;"><img
                src="https://fakestoreapi.com/img/71kWymZ+c+L._AC_SX679_.jpg" class="bd-placeholder-img card-img-top">
              <div class="card-body">
                <h5 class="card-title">Silicon Power 256GB SSD 3D NAND A55 SLC Cache Performance Boost SATA III 2.5</h5>
                <h3 class="card-title">7630 ₽</h3>
                <p class="card-text">3D NAND flash are applied to deliver high transfer speeds Remarkable transfer
                  speeds that enable faster bootup and improved overall system performance. The advanced SLC Cache
                  Technology allows performance boost and longer lifespan 7mm slim design suitable for Ultrabooks and
                  Ultra-slim notebooks. Supports TRIM command, Garbage Collection technology, RAID, and ECC (Error
                  Checking &amp; Correction) to provide the optimized performance and enhanced reliability.</p>
                <div class="d-flex justify-content-between align-items-center">
                  <div class="btn-group"><button type="button"
                      class="btn btn-sm btn-outline-secondary">Заказать</button></div>
                </div>
              </div>
            </div>
          </div>
          <div class="col">
            <div class="card shadow-sm" style="padding: 12px;"><img
                src="https://fakestoreapi.com/img/61mtL65D4cL._AC_SX679_.jpg" class="bd-placeholder-img card-img-top">
              <div class="card-body">
                <h5 class="card-title">WD 4TB Gaming Drive Works with Playstation 4 Portable External Hard Drive</h5>
                <h3 class="card-title">7980 ₽</h3>
                <p class="card-text">Expand your PS4 gaming experience, Play anywhere Fast and easy, setup Sleek design
                  with high capacity, 3-year manufacturer's limited warranty</p>
                <div class="d-flex justify-content-between align-items-center">
                  <div class="btn-group"><button type="button"
                      class="btn btn-sm btn-outline-secondary">Заказать</button></div>
                </div>
              </div>
            </div>
          </div>
          <div class="col">
            <div class="card shadow-sm" style="padding: 12px;"><img
                src="https://fakestoreapi.com/img/81QpkIctqPL._AC_SX679_.jpg" class="bd-placeholder-img card-img-top">
              <div class="card-body">
                <h5 class="card-title">Acer SB220Q bi 21.5 inches Full HD (1920 x 1080) IPS Ultra-Thin</h5>
                <h3 class="card-title">41930 ₽</h3>
                <p class="card-text">21. 5 inches Full HD (1920 x 1080) widescreen IPS display And Radeon free Sync
                  technology. No compatibility for VESA Mount Refresh Rate: 75Hz - Using HDMI port Zero-frame design |
                  ultra-thin | 4ms response time | IPS panel Aspect ratio - 16: 9. Color Supported - 16. 7 million
                  colors. Brightness - 250 nit Tilt angle -5 degree to 15 degree. Horizontal viewing angle-178 degree.
                  Vertical viewing angle-178 degree 75 hertz</p>
                <div class="d-flex justify-content-between align-items-center">
                  <div class="btn-group"><button type="button"
                      class="btn btn-sm btn-outline-secondary">Заказать</button></div>
                </div>
              </div>
            </div>
          </div>
          <div class="col">
            <div class="card shadow-sm" style="padding: 12px;"><img
                src="https://fakestoreapi.com/img/81Zt42ioCgL._AC_SX679_.jpg" class="bd-placeholder-img card-img-top">
              <div class="card-body">
                <h5 class="card-title">Samsung 49-Inch CHG90 144Hz Curved Gaming Monitor (LC49HG90DMNXZA) – Super
                  Ultrawide Screen QLED </h5>
                <h3 class="card-title">69999.3 ₽</h3>
                <p class="card-text">49 INCH SUPER ULTRAWIDE 32:9 CURVED GAMING MONITOR with dual 27 inch screen side by
                  side QUANTUM DOT (QLED) TECHNOLOGY, HDR support and factory calibration provides stunningly realistic
                  and accurate color and contrast 144HZ HIGH REFRESH RATE and 1ms ultra fast response time work to
                  eliminate motion blur, ghosting, and reduce input lag</p>
                <div class="d-flex justify-content-between align-items-center">
                  <div class="btn-group"><button type="button"
                      class="btn btn-sm btn-outline-secondary">Заказать</button></div>
                </div>
              </div>
            </div>
          </div>
          <div class="col">
            <div class="card shadow-sm" style="padding: 12px;"><img
                src="https://fakestoreapi.com/img/51Y5NI-I5jL._AC_UX679_.jpg" class="bd-placeholder-img card-img-top">
              <div class="card-body">
                <h5 class="card-title">BIYLACLESEN Women's 3-in-1 Snowboard Jacket Winter Coats</h5>
                <h3 class="card-title">3989.3 ₽</h3>
                <p class="card-text">Note:The Jackets is US standard size, Please choose size as your usual wear
                  Material: 100% Polyester; Detachable Liner Fabric: Warm Fleece. Detachable Functional Liner: Skin
                  Friendly, Lightweigt and Warm.Stand Collar Liner jacket, keep you warm in cold weather. Zippered
                  Pockets: 2 Zippered Hand Pockets, 2 Zippered Pockets on Chest (enough to keep cards or keys)and 1
                  Hidden Pocket Inside.Zippered Hand Pockets and Hidden Pocket keep your things secure. Humanized
                  Design: Adjustable and Detachable Hood and Adjustable cuff to prevent the wind and water,for a
                  comfortable fit. 3 in 1 Detachable Design provide more convenience, you can separate the coat and
                  inner as needed, or wear it together. It is suitable for different season and help you adapt to
                  different climates</p>
                <div class="d-flex justify-content-between align-items-center">
                  <div class="btn-group"><button type="button"
                      class="btn btn-sm btn-outline-secondary">Заказать</button></div>
                </div>
              </div>
            </div>
          </div>
          <div class="col">
            <div class="card shadow-sm" style="padding: 12px;"><img
                src="https://fakestoreapi.com/img/81XH0e8fefL._AC_UY879_.jpg" class="bd-placeholder-img card-img-top">
              <div class="card-body">
                <h5 class="card-title">Lock and Love Women's Removable Hooded Faux Leather Moto Biker Jacket</h5>
                <h3 class="card-title">2096.5 ₽</h3>
                <p class="card-text">100% POLYURETHANE(shell) 100% POLYESTER(lining) 75% POLYESTER 25% COTTON (SWEATER),
                  Faux leather material for style and comfort / 2 pockets of front, 2-For-One Hooded denim style faux
                  leather jacket, Button detail on waist / Detail stitching at sides, HAND WASH ONLY / DO NOT BLEACH /
                  LINE DRY / DO NOT IRON</p>
                <div class="d-flex justify-content-between align-items-center">
                  <div class="btn-group"><button type="button"
                      class="btn btn-sm btn-outline-secondary">Заказать</button></div>
                </div>
              </div>
            </div>
          </div>
          <div class="col">
            <div class="card shadow-sm" style="padding: 12px;"><img
                src="https://fakestoreapi.com/img/71HblAHs5xL._AC_UY879_-2.jpg" class="bd-placeholder-img card-img-top">
              <div class="card-body">
                <h5 class="card-title">Rain Jacket Women Windbreaker Striped Climbing Raincoats</h5>
                <h3 class="card-title">2799.3 ₽</h3>
                <p class="card-text">Lightweight perfet for trip or casual wear---Long sleeve with hooded, adjustable
                  drawstring waist design. Button and zipper front closure raincoat, fully stripes Lined and The
                  Raincoat has 2 side pockets are a good size to hold all kinds of things, it covers the hips, and the
                  hood is generous but doesn't overdo it.Attached Cotton Lined Hood with Adjustable Drawstrings give it
                  a real styled look.</p>
                <div class="d-flex justify-content-between align-items-center">
                  <div class="btn-group"><button type="button"
                      class="btn btn-sm btn-outline-secondary">Заказать</button></div>
                </div>
              </div>
            </div>
          </div>
          <div class="col">
            <div class="card shadow-sm" style="padding: 12px;"><img
                src="https://fakestoreapi.com/img/71z3kpMAYsL._AC_UY879_.jpg" class="bd-placeholder-img card-img-top">
              <div class="card-body">
                <h5 class="card-title">MBJ Women's Solid Short Sleeve Boat Neck V </h5>
                <h3 class="card-title">689.5 ₽</h3>
                <p class="card-text">95% RAYON 5% SPANDEX, Made in USA or Imported, Do Not Bleach, Lightweight fabric
                  with great stretch for comfort, Ribbed on sleeves and neckline / Double stitching on bottom hem</p>
                <div class="d-flex justify-content-between align-items-center">
                  <div class="btn-group"><button type="button"
                      class="btn btn-sm btn-outline-secondary">Заказать</button></div>
                </div>
              </div>
            </div>
          </div>
          <div class="col">
            <div class="card shadow-sm" style="padding: 12px;"><img
                src="https://fakestoreapi.com/img/51eg55uWmdL._AC_UX679_.jpg" class="bd-placeholder-img card-img-top">
              <div class="card-body">
                <h5 class="card-title">Opna Women's Short Sleeve Moisture</h5>
                <h3 class="card-title">556.5 ₽</h3>
                <p class="card-text">100% Polyester, Machine wash, 100% cationic polyester interlock, Machine Wash &amp;
                  Pre Shrunk for a Great Fit, Lightweight, roomy and highly breathable with moisture wicking fabric
                  which helps to keep moisture away, Soft Lightweight Fabric with comfortable V-neck collar and a
                  slimmer fit, delivers a sleek, more feminine silhouette and Added Comfort</p>
                <div class="d-flex justify-content-between align-items-center">
                  <div class="btn-group"><button type="button"
                      class="btn btn-sm btn-outline-secondary">Заказать</button></div>
                </div>
              </div>
            </div>
          </div>
          <div class="col">
            <div class="card shadow-sm" style="padding: 12px;"><img
                src="https://fakestoreapi.com/img/61pHAEJ4NML._AC_UX679_.jpg" class="bd-placeholder-img card-img-top">
              <div class="card-body">
                <h5 class="card-title">DANVOUY Womens T Shirt Casual Cotton Short</h5>
                <h3 class="card-title">909.3000000000001 ₽</h3>
                <p class="card-text">95%Cotton,5%Spandex, Features: Casual, Short Sleeve, Letter Print,V-Neck,Fashion
                  Tees, The fabric is soft and has some stretch., Occasion: Casual/Office/Beach/School/Home/Street.
                  Season: Spring,Summer,Autumn,Winter.</p>
                <div class="d-flex justify-content-between align-items-center">
                  <div class="btn-group"><button type="button"
                      class="btn btn-sm btn-outline-secondary">Заказать</button></div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

  </div>
</div></template>

<script>
export default {
  name: 'App',
}
</script>

<style></style>
