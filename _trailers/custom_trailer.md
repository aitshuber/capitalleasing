---
layout: default
seo:
  title:
  description:
  keywords:
  image:
name: 2014 Horse Trailer
trailer_type: Custom Trailer
description: Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
specifications:
  - name: Manufacturing year
    feature: 2021
  - name: Mileage
    feature: 60K miles
  - name: Body type
    feature: Convertible
  - name: Drive type
    feature: 2 wheel drive - rear
  - name: Engine
    feature: 6-Cylinder Turbo
  - name: Transmission
    feature: 7-Speed Shiftable Automatic
  - name: Fuel type
    feature: Gasoline
  - name: City MPG
    feature: 20
  - name: Highway MPG
    feature: 28
  - name: Exterior color
    feature: Red
  - name: Interior color
    feature: Charcoal
  - name: VIN
    feature: 2VW821AU9JM754284
exterior:
  - Lorem ipsum dolor sit amet
  - Lorem ipsum dolor sit amet
  - Lorem ipsum dolor sit amet
  - Lorem ipsum dolor sit amet
  - Lorem ipsum dolor sit amet
  - Lorem ipsum dolor sit amet
  - Lorem ipsum dolor sit amet
  - Lorem ipsum dolor sit amet
  - Lorem ipsum dolor sit amet
  - Lorem ipsum dolor sit amet
  - Lorem ipsum dolor sit amet
  - Lorem ipsum dolor sit amet
interior:
  - Lorem ipsum dolor sit amet
  - Lorem ipsum dolor sit amet
  - Lorem ipsum dolor sit amet
  - Lorem ipsum dolor sit amet
  - Lorem ipsum dolor sit amet
  - Lorem ipsum dolor sit amet
  - Lorem ipsum dolor sit amet
  - Lorem ipsum dolor sit amet
  - Lorem ipsum dolor sit amet
  - Lorem ipsum dolor sit amet
  - Lorem ipsum dolor sit amet
  - Lorem ipsum dolor sit amet
gallery:
  - image: /assets/img/trailers/image-asset.jpg
  - image: /assets/img/trailers/custom/2017-10-19+11.27.46.jpg
  - image: /assets/img/trailers/custom/2017-10-19+11.29.20.jpg
  - image: /assets/img/trailers/custom/2017-10-19+11.44.41.jpg
  - image: /assets/img/trailers/custom/2017-10-19+11.45.38.jpg
video:
price: $192,500
features:
  - item: 45' LENGTH
  - item: Custom Options
  - item: Gooseneck
---
  <!-- Car details section -->
  <section class="container pt-4 pb-5 mb-xxl-3">
	<!-- Title + Share button -->
	<div class="d-flex justify-content-between gap-3 position-relative z-2 mb-3 mb-lg-4">
	  <h1 class="mb-0">{{page.name}}</h1>
	  <div class="d-flex gap-2">
		<div class="dropdown" data-bs-toggle="tooltip" data-bs-custom-class="tooltip-sm" title="Share">
		  <button type="button" class="btn btn-icon btn-ghost btn-secondary animate-scale rounded-circle" data-bs-toggle="dropdown" aria-haspopup="true" aria-expanded="false" aria-label="Share">
			<i class="fi-share-2 animate-target fs-base"></i>
		  </button>
		</div>
	  </div>
	</div>
	<!-- Listing meta visible on screens < 992px wide (lg breakpoint) -->
	<div class="d-lg-none mb-4">
	  <div class="d-flex align-items-center justify-content-between gap-3 pb-1 mb-2">
		<div class="h2 mb-0">{{page.price}}</div>
		<div class="d-flex gap-2 mb-3">
		  <span class="badge text-bg-info d-inline-flex align-items-center">
			Verified
			<i class="fi-shield ms-1"></i>
		  </span>
		  <span class="badge text-bg-warning">Used</span>
		</div>
	  </div>
	  <div class="d-flex flex-wrap gap-2 gap-sm-3 fs-sm text-nowrap">
		<div class="d-flex align-items-center gap-2 me-2">
		  <i class="fi-map-pin"></i>
		  Chicago
		</div>
		<div class="d-flex align-items-center gap-2 me-2">
		  <i class="fi-tachometer"></i>
		  60K mi
		</div>
		<div class="d-flex align-items-center gap-2 me-2">
		  <i class="fi-gas-pump"></i>
		  Gasoline
		</div>
		<div class="d-flex align-items-center gap-2">
		  <i class="fi-gearbox"></i>
		  Automatic
		</div>
	  </div>
	</div>
	<div class="row">
	  <!-- Gallery (slider) + Description -->
	  <div class="col-lg-8 pb-3 pb-sm-0 mb-4 mb-sm-5 mb-lg-0">
		<!-- Main slider -->
		<div class="swiper hover-effect-opacity" data-swiper='{
		  "spaceBetween": 16,
		  "loop": true,
		  "navigation": {
			"prevEl": ".btn-prev",
			"nextEl": ".btn-next"
		  },
		  "thumbs": {
			"swiper": "#thumbs"
		  }
		}'>
		  <div class="swiper-wrapper">
			  {% for item in page.gallery %}
			<div class="swiper-slide">
			  <div class="ratio bg-body-tertiary rounded overflow-hidden gallery-ratio">
				<img src="{{item.image}}" class="object-cover" alt="Image">
			  </div>
			</div>
			{% endfor %}
		  </div>
		  <!-- Prev / next buttons -->
		  <div class="position-absolute top-50 start-0 z-2 translate-middle-y ms-3 ms-sm-4 hover-effect-target opacity-0">
			<button type="button" class="btn btn-prev btn-icon btn-secondary bg-body border-0 rounded-circle animate-slide-start" aria-label="Prev" data-bs-theme="light">
			  <i class="fi-chevron-left fs-lg animate-target"></i>
			</button>
		  </div>
		  <div class="position-absolute top-50 end-0 z-2 translate-middle-y me-3 me-sm-4 hover-effect-target opacity-0">
			<button type="button" class="btn btn-next btn-icon btn-secondary bg-body border-0 rounded-circle animate-slide-end" aria-label="Next" data-bs-theme="light">
			  <i class="fi-chevron-right fs-lg animate-target"></i>
			</button>
		  </div>
		</div>
		<!-- Thumbnails slider -->
		<div class="swiper swiper-load swiper-thumbs pt-2 mt-1" id="thumbs" data-swiper='{
		  "loop": true,
		  "spaceBetween": 16,
		  "slidesPerView": 3,
		  "watchSlidesProgress": true,
		  "breakpoints": {
			"340": {
			  "slidesPerView": 4
			},
			"500": {
			  "slidesPerView": 5
			},
			"600": {
			  "slidesPerView": 6
			},
			"768": {
			  "slidesPerView": 4
			},
			"992": {
			  "slidesPerView": 5
			},
			"1200": {
			  "slidesPerView": 5
			}
		  }
		}'>
		  <div class="swiper-wrapper">
			{% for item in page.gallery %}
			<div class="swiper-slide swiper-thumb overflow-hidden">
			  <div class="ratio bg-body-tertiary gallery-ratio-thumb" >
				<img src="{{item.image}}" class="swiper-thumb-img object-cover" alt="Thumbnail">
			  </div>
			</div>
			{% endfor %}
		  </div>
		</div>
		<!-- Specifications -->
		<h2 class="h3 pt-5 mt-sm-2 my-lg-4">Specifications</h2>
		{% assign spec_half_size = page.specifications.size | divided_by: 2 %}
		<div class="row row-cols-1 row-cols-sm-2 gy-2">
		  <div class="col">
			<ul class="list-unstyled text-body-secondary mt-n1 mb-0">
			  {% for item in page.specifications limit: spec_half_size %}
			  <li class="mt-1">
				<span class="fw-medium text-dark-emphasis me-1">{{item.name}}:</span>
				{{item.feature}}
			  </li>
			  {% endfor %}
			</ul>
		  </div>
		  <div class="col">
			<ul class="list-unstyled text-body-secondary mt-n1 mb-0">
			{% for item in page.specifications offset: spec_half_size %}
			  <li class="mt-1">
				<span class="fw-medium text-dark-emphasis me-1">{{item.name}}:</span>
				{{item.feature}}
			  </li>
			  {% endfor %}
			</ul>
		  </div>
		</div>
		<!-- Fetures (Accordion) -->
		<h2 class="h3 pt-5 mt-sm-2 mb-2 mb-lg-3">Features</h2>
		<div class="accordion accordion-alt-icon" id="features">
		  <div class="accordion-item">
			<h3 class="accordion-header" id="headingExterior">
			  <button type="button" class="accordion-button fs-5 collapsed" data-bs-toggle="collapse" data-bs-target="#exterior" aria-expanded="false" aria-controls="exterior">
				<span class="stretched-link me-2">Exterior</span>
			  </button>
			</h3>
			<div class="accordion-collapse collapse" id="exterior" aria-labelledby="headingExterior" data-bs-parent="#features">
			  <div class="accordion-body fs-base">
				<div class="row row-cols-1 row-cols-sm-2 gy-2">
					{% assign exterior_half_size = page.exterior.size | divided_by: 2 %}
				  <div class="col">
					<ul class="mt-n1 mb-0">
					 {% for exterior_half_size_1 in page.exterior limit: exterior_half_size %}
						 <li class="mt-1">{{ exterior_half_size_1 }}</li>
					   {% endfor %}
					</ul>
				  </div>
				  <div class="col">
					<ul class="mt-n1 mb-0">
					 {% for exterior_half_size_2 in page.exterior offset: exterior_half_size %}
						 <li class="mt-1">{{ exterior_half_size_2 }}</li>
					   {% endfor %}
					</ul>
				  </div>
				</div>
			  </div>
		  </div>
		  </div>
		  <div class="accordion-item">
			<h3 class="accordion-header" id="headingInterior">
			  <button type="button" class="accordion-button fs-5 collapsed" data-bs-toggle="collapse" data-bs-target="#interior" aria-expanded="true" aria-controls="interior">
				<span class="stretched-link me-2">Interior</span>
			  </button>
			</h3>
			<div class="accordion-collapse collapse" id="interior" aria-labelledby="headingInterior" data-bs-parent="#features">
			  <div class="accordion-body fs-base">
				<div class="row row-cols-1 row-cols-sm-2 gy-2">
					{% assign half_size = page.interior.size | divided_by: 2 %}
				  <div class="col">
					<ul class="mt-n1 mb-0">
					 {% for feature in page.interior limit: half_size %}
						 <li class="mt-1">{{ feature }}</li>
					   {% endfor %}
					</ul>
				  </div>
				  <div class="col">
					<ul class="mt-n1 mb-0">
					 {% for feature in page.interior offset: half_size %}
						 <li class="mt-1">{{ feature }}</li>
					   {% endfor %}
					</ul>
				  </div>
				</div>
			  </div>
			</div>
		  </div>
		</div>
		<!-- Seller's description -->
		<h2 class="h3 pt-5 mt-sm-2">Description</h2>
		{% assign first_half = page.description | truncatewords: 50 | remove: '...' %}
		{% assign words = page.description | split: ' ' %}
		{% assign first_half = words | slice: 0, 50 | join: ' ' %}
		{% assign second_half = words | slice: 50, words.size | join: ' ' %}
		<p>{{ first_half }}</p>
		<div class="collapse" id="moreDescription">
		  <p>{{ second_half }}</p>
		</div>
		<div class="nav">
		  <a class="nav-link position-relative px-0 collapsed" href="#moreDescription" data-bs-toggle="collapse" aria-expanded="false" aria-controls="moreDescription" aria-label="Show / hide services">
			<span class="hover-effect-underline stretched-link" data-label-collapsed="Show more" data-label-expanded="Show less"></span>
			<i class="collapse-toggle-icon fi-chevron-down fs-base mt-1 ms-1"></i>
		  </a>
		</div>
	  </div>
	  <!-- Sidebar with car detail and seller info -->
	  <aside class="col-lg-4" style="margin-top: -110px">
		<div class="position-sticky top-0" style="padding-top: 110px">
		  <!-- Listing meta visible on screens > 991px (lg breakpoint) -->
		  <div class="d-none d-lg-block">
			<div class="h2 pb-1 mb-2">{{page.price}}</div>
			<div class="d-flex flex-wrap justify-content-lg-between gap-2 fs-sm text-nowrap mb-4">
			  {% for list in page.features limit: 3 %}
				<div class="d-flex align-items-center gap-2">
				  <i class="fal fa-chevron-right icon-size"></i>
				 {{list.item}}
				</div>
				{% endfor %}
			</div>
		  </div>
		  <!-- Seller info card -->
		  <div class="card bg-body-tertiary border-0 p-sm-2 p-lg-0 p-xl-2 mb-4">
			<div class="card-body">
			  <div class="d-flex align-items-center position-relative mb-3">
				<div class="">
				  <img src="/assets/img/logo.svg" class="w-75" alt="Avatar">
				</div>
			  </div>
			  <div class="d-flex flex-wrap gap-3">
				<p>{{site.data.company_details.phone}}</p>
			  </div>
			</div>
		  </div>
		  <!-- Subscribe -->
		  <div class="card p-sm-2 p-lg-0 p-xl-2">
			<div class="card-body">
			  <h4 class="h6">Email me price drops and new listings for these search results:</h4>
			  <form class="needs-validation d-flex flex-column flex-sm-row flex-lg-column flex-xl-row gap-2 gap-sm-3 gap-lg-2 gap-xl-3 mb-3" novalidate>
				<div class="position-relative">
				  <i class="fi-mail position-absolute top-50 start-0 translate-middle-y ms-3"></i>
				  <input type="email" class="form-control form-icon-start" placeholder="Your email" required>
				</div>
				<button type="submit" class="btn btn-secondary">Subscribe</button>
			  </form>
			</div>
		  </div>
		</div>
	  </aside>
	</div>
  </section>
