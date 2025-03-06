# HelloWorld
Test - 
 It is just a test to help me to learn how to code. 
 I don't know even why I am using this hashtag, by the way, if you know teach me

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Glow - Natural Skincare Products</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Pacifico&family=DM+Sans:opsz,wght@9..40,300;9..40,400;9..40,500;9..40,600&display=swap"
      rel="stylesheet"
    />
    <link
      href="https://cdn.jsdelivr.net/npm/remixicon@4.5.0/fonts/remixicon.css"
      rel="stylesheet"
    />
    <style>
      :where([class^="ri-"])::before { content: "\f3c2"; }
      .hide-scroll::-webkit-scrollbar {display: none;}
      .hide-scroll {-ms-overflow-style: none;scrollbar-width: none;}
    </style>
    <script>
      tailwind.config = {
        theme: {
          extend: {
            colors: {
              primary: "#D4B499",
              secondary: "#F5EBE0",
            },
            borderRadius: {
              none: "0px",
              sm: "4px",
              DEFAULT: "8px",
              md: "12px",
              lg: "16px",
              xl: "20px",
              "2xl": "24px",
              "3xl": "32px",
              full: "9999px",
              button: "8px",
            },
          },
        },
      };
    </script>
  </head>
  <body class="font-['DM_Sans'] bg-white">
    <header
      class="fixed top-0 left-0 right-0 bg-white/80 backdrop-blur-md z-50 border-b border-gray-100"
    >
      <div class="max-w-7xl mx-auto px-4">
        <nav class="flex items-center justify-between h-20">
          <a href="#" class="font-['Pacifico'] text-2xl">logo</a>

          <div class="hidden md:flex items-center space-x-8">
            <a
              href="#"
              class="text-gray-700 hover:text-primary transition-colors"
              >Skincare</a
            >
            <a
              href="#"
              class="text-gray-700 hover:text-primary transition-colors"
              >New Arrivals</a
            >
            <a
              href="#"
              class="text-gray-700 hover:text-primary transition-colors"
              >Best Sellers</a
            >
            <a
              href="#"
              class="text-gray-700 hover:text-primary transition-colors"
              >About</a
            >
            <a
              href="#"
              class="text-gray-700 hover:text-primary transition-colors"
              >Contact</a
            >
          </div>

          <div class="flex items-center space-x-6">
            <div class="relative">
              <input
                type="text"
                placeholder="Search products..."
                class="w-64 pl-10 pr-4 py-2 text-sm bg-gray-50 rounded-full border-none focus:ring-2 focus:ring-primary/20 focus:outline-none"
              />
              <div
                class="absolute left-3 top-1/2 -translate-y-1/2 w-4 h-4 flex items-center justify-center text-gray-400"
              >
                <i class="ri-search-line"></i>
              </div>
            </div>

            <div
              class="relative cursor-pointer w-10 h-10 flex items-center justify-center"
            >
              <i class="ri-shopping-bag-line text-xl"></i>
              <span
                class="absolute -top-1 -right-1 w-5 h-5 bg-primary text-white text-xs rounded-full flex items-center justify-center"
                >3</span
              >
            </div>

            <div
              class="w-10 h-10 flex items-center justify-center cursor-pointer"
            >
              <i class="ri-user-line text-xl"></i>
            </div>
          </div>
        </nav>
      </div>
    </header>

    <main class="pt-20">
      <section class="relative h-[600px] bg-secondary overflow-hidden">
        <div class="absolute inset-0">
          <img
            src="https://public.readdy.ai/ai/img_res/8adff292f0e0aa348c450daa3e23418f.jpg"
            class="w-full h-full object-cover object-center"
            alt="Hero Image"
          />
        </div>
        <div class="relative max-w-7xl mx-auto px-4 h-full flex items-center">
          <div class="max-w-xl">
            <h1 class="text-5xl font-light leading-tight mb-6">
              Discover Your Natural Beauty with Pure Ingredients
            </h1>
            <p class="text-lg text-gray-700 mb-8">
              Experience the transformation with our premium skincare
              collection, crafted with nature's finest ingredients for radiant,
              healthy skin.
            </p>
            <button
              class="bg-primary text-white px-8 py-3 rounded-button text-lg hover:bg-primary/90 transition-colors"
            >
              Shop Now
            </button>
          </div>
        </div>
      </section>

      <section class="py-20 bg-white">
        <div class="max-w-7xl mx-auto px-4">
          <h2 class="text-3xl text-center mb-16">Best Sellers</h2>
          <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">
            <div class="group relative">
              <div class="aspect-square rounded-lg overflow-hidden bg-gray-100">
                <img
                  src="https://public.readdy.ai/ai/img_res/180451b66d0cb5732bb60dd413a260b4.jpg"
                  class="w-full h-full object-cover"
                  alt="Product 1"
                />
              </div>
              <div class="mt-4">
                <h3 class="text-lg font-medium">Hydrating Face Cream</h3>
                <p class="text-gray-600 text-sm mt-1">
                  Rich moisturizer with hyaluronic acid
                </p>
                <div class="flex items-center justify-between mt-2">
                  <span class="text-lg">$48.00</span>
                  <button
                    class="bg-primary text-white px-4 py-2 rounded-button text-sm hover:bg-primary/90 transition-colors"
                  >
                    Add to Cart
                  </button>
                </div>
              </div>
            </div>

            <div class="group relative">
              <div class="aspect-square rounded-lg overflow-hidden bg-gray-100">
                <img
                  src="https://public.readdy.ai/ai/img_res/9e3e56fe10edbac9d356bf897143f2a6.jpg"
                  class="w-full h-full object-cover"
                  alt="Product 2"
                />
              </div>
              <div class="mt-4">
                <h3 class="text-lg font-medium">Vitamin C Serum</h3>
                <p class="text-gray-600 text-sm mt-1">
                  Brightening and anti-aging formula
                </p>
                <div class="flex items-center justify-between mt-2">
                  <span class="text-lg">$56.00</span>
                  <button
                    class="bg-primary text-white px-4 py-2 rounded-button text-sm hover:bg-primary/90 transition-colors"
                  >
                    Add to Cart
                  </button>
                </div>
              </div>
            </div>

            <div class="group relative">
              <div class="aspect-square rounded-lg overflow-hidden bg-gray-100">
                <img
                  src="https://public.readdy.ai/ai/img_res/0bf9f0fa8747a0d59a3bf463dc436e97.jpg"
                  class="w-full h-full object-cover"
                  alt="Product 3"
                />
              </div>
              <div class="mt-4">
                <h3 class="text-lg font-medium">Gentle Cleansing Gel</h3>
                <p class="text-gray-600 text-sm mt-1">
                  Sulfate-free daily cleanser
                </p>
                <div class="flex items-center justify-between mt-2">
                  <span class="text-lg">$32.00</span>
                  <button
                    class="bg-primary text-white px-4 py-2 rounded-button text-sm hover:bg-primary/90 transition-colors"
                  >
                    Add to Cart
                  </button>
                </div>
              </div>
            </div>

            <div class="group relative">
              <div class="aspect-square rounded-lg overflow-hidden bg-gray-100">
                <img
                  src="https://public.readdy.ai/ai/img_res/9d4485d3fc107eabdb903d307d26e43c.jpg"
                  class="w-full h-full object-cover"
                  alt="Product 4"
                />
              </div>
              <div class="mt-4">
                <h3 class="text-lg font-medium">Overnight Repair Mask</h3>
                <p class="text-gray-600 text-sm mt-1">
                  Intensive healing treatment
                </p>
                <div class="flex items-center justify-between mt-2">
                  <span class="text-lg">$42.00</span>
                  <button
                    class="bg-primary text-white px-4 py-2 rounded-button text-sm hover:bg-primary/90 transition-colors"
                  >
                    Add to Cart
                  </button>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>

      <section class="py-20 bg-secondary/30">
        <div class="max-w-7xl mx-auto px-4">
          <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
            <div class="text-center">
              <div
                class="w-16 h-16 mx-auto mb-4 flex items-center justify-center"
              >
                <i class="ri-leaf-line text-3xl text-primary"></i>
              </div>
              <h3 class="text-xl font-medium mb-2">Natural Ingredients</h3>
              <p class="text-gray-600">
                Carefully sourced botanical ingredients that nourish your skin
                naturally
              </p>
            </div>

            <div class="text-center">
              <div
                class="w-16 h-16 mx-auto mb-4 flex items-center justify-center"
              >
                <i class="ri-test-tube-line text-3xl text-primary"></i>
              </div>
              <h3 class="text-xl font-medium mb-2">Dermatologist Tested</h3>
              <p class="text-gray-600">
                All products are tested and approved by certified dermatologists
              </p>
            </div>

            <div class="text-center">
              <div
                class="w-16 h-16 mx-auto mb-4 flex items-center justify-center"
              >
                <i class="ri-heart-line text-3xl text-primary"></i>
              </div>
              <h3 class="text-xl font-medium mb-2">Cruelty Free</h3>
              <p class="text-gray-600">
                Never tested on animals and certified by Leaping Bunny Program
              </p>
            </div>
          </div>
        </div>
      </section>

      <section class="py-20 bg-white">
        <div class="max-w-7xl mx-auto px-4">
          <h2 class="text-3xl text-center mb-16">Shop by Category</h2>
          <div class="flex space-x-6 overflow-x-auto hide-scroll pb-4">
            <div class="min-w-[280px] rounded-lg overflow-hidden">
              <div class="aspect-[4/5] relative">
                <img
                  src="https://public.readdy.ai/ai/img_res/79cc6b6437f6d0418ead1c925c405be1.jpg"
                  class="w-full h-full object-cover"
                  alt="Cleansers"
                />
                <div class="absolute inset-0 bg-black/20"></div>
                <div class="absolute bottom-0 left-0 right-0 p-6 text-white">
                  <h3 class="text-xl font-medium mb-2">Cleansers</h3>
                  <p class="text-sm opacity-90">Start with a clean canvas</p>
                </div>
              </div>
            </div>

            <div class="min-w-[280px] rounded-lg overflow-hidden">
              <div class="aspect-[4/5] relative">
                <img
                  src="https://public.readdy.ai/ai/img_res/e97b6db804f01fc12fb1af97b463c24b.jpg"
                  class="w-full h-full object-cover"
                  alt="Moisturizers"
                />
                <div class="absolute inset-0 bg-black/20"></div>
                <div class="absolute bottom-0 left-0 right-0 p-6 text-white">
                  <h3 class="text-xl font-medium mb-2">Moisturizers</h3>
                  <p class="text-sm opacity-90">Lock in hydration</p>
                </div>
              </div>
            </div>

            <div class="min-w-[280px] rounded-lg overflow-hidden">
              <div class="aspect-[4/5] relative">
                <img
                  src="https://public.readdy.ai/ai/img_res/5b25c3d15d39f9fb6813f917b2840fce.jpg"
                  class="w-full h-full object-cover"
                  alt="Serums"
                />
                <div class="absolute inset-0 bg-black/20"></div>
                <div class="absolute bottom-0 left-0 right-0 p-6 text-white">
                  <h3 class="text-xl font-medium mb-2">Serums</h3>
                  <p class="text-sm opacity-90">Target specific concerns</p>
                </div>
              </div>
            </div>

            <div class="min-w-[280px] rounded-lg overflow-hidden">
              <div class="aspect-[4/5] relative">
                <img
                  src="https://public.readdy.ai/ai/img_res/6ed51eb053943e1a6df88c77d2eeb081.jpg"
                  class="w-full h-full object-cover"
                  alt="Treatments"
                />
                <div class="absolute inset-0 bg-black/20"></div>
                <div class="absolute bottom-0 left-0 right-0 p-6 text-white">
                  <h3 class="text-xl font-medium mb-2">Treatments</h3>
                  <p class="text-sm opacity-90">Extra care for your skin</p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>

      <section class="py-20 bg-secondary/30">
        <div class="max-w-7xl mx-auto px-4">
          <h2 class="text-3xl text-center mb-16">Customer Reviews</h2>
          <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
            <div class="bg-white p-6 rounded-lg shadow-sm">
              <div class="flex items-center text-yellow-400 mb-4">
                <i class="ri-star-fill"></i>
                <i class="ri-star-fill"></i>
                <i class="ri-star-fill"></i>
                <i class="ri-star-fill"></i>
                <i class="ri-star-fill"></i>
              </div>
              <p class="text-gray-600 mb-4">
                "The Hydrating Face Cream has completely transformed my skin.
                It's so moisturizing without feeling heavy. My skin feels plump
                and healthy!"
              </p>
              <div class="flex items-center">
                <span class="text-sm font-medium">Emma Thompson</span>
                <span class="mx-2 text-gray-300">|</span>
                <span class="text-sm text-gray-500">Verified Purchase</span>
              </div>
            </div>

            <div class="bg-white p-6 rounded-lg shadow-sm">
              <div class="flex items-center text-yellow-400 mb-4">
                <i class="ri-star-fill"></i>
                <i class="ri-star-fill"></i>
                <i class="ri-star-fill"></i>
                <i class="ri-star-fill"></i>
                <i class="ri-star-fill"></i>
              </div>
              <p class="text-gray-600 mb-4">
                "I'm obsessed with the Vitamin C Serum! My dark spots have
                significantly faded and my skin is glowing. Worth every penny!"
              </p>
              <div class="flex items-center">
                <span class="text-sm font-medium">Sarah Anderson</span>
                <span class="mx-2 text-gray-300">|</span>
                <span class="text-sm text-gray-500">Verified Purchase</span>
              </div>
            </div>

            <div class="bg-white p-6 rounded-lg shadow-sm">
              <div class="flex items-center text-yellow-400 mb-4">
                <i class="ri-star-fill"></i>
                <i class="ri-star-fill"></i>
                <i class="ri-star-fill"></i>
                <i class="ri-star-fill"></i>
                <i class="ri-star-fill"></i>
              </div>
              <p class="text-gray-600 mb-4">
                "The Overnight Repair Mask is a game changer! I wake up with
                such soft and refreshed skin. It's now a permanent part of my
                routine."
              </p>
              <div class="flex items-center">
                <span class="text-sm font-medium">Michelle Parker</span>
                <span class="mx-2 text-gray-300">|</span>
                <span class="text-sm text-gray-500">Verified Purchase</span>
              </div>
            </div>
          </div>
        </div>
      </section>

      <section class="py-20 bg-white">
        <div class="max-w-7xl mx-auto px-4">
          <div class="max-w-xl mx-auto text-center">
            <h2 class="text-3xl mb-4">Join Our Newsletter</h2>
            <p class="text-gray-600 mb-8">
              Subscribe to receive updates, access to exclusive deals, and more.
            </p>
            <form class="flex gap-4">
              <input
                type="email"
                placeholder="Enter your email"
                class="flex-1 px-4 py-3 rounded-button border-none bg-gray-50 focus:ring-2 focus:ring-primary/20"
              />
              <button
                type="submit"
                class="bg-primary text-white px-6 py-3 rounded-button hover:bg-primary/90 transition-colors"
              >
                Subscribe
              </button>
            </form>
            <p class="text-sm text-gray-500 mt-4">
              Get 10% off your first order when you sign up!
            </p>
          </div>
        </div>
      </section>
    </main>

    <footer class="bg-gray-900 text-white py-20">
      <div class="max-w-7xl mx-auto px-4">
        <div class="grid grid-cols-1 md:grid-cols-4 gap-12">
          <div>
            <a href="#" class="font-['Pacifico'] text-2xl block mb-6">logo</a>
            <p class="text-gray-400">
              Premium skincare products made with natural ingredients for
              healthy, glowing skin.
            </p>
          </div>

          <div>
            <h3 class="text-lg font-medium mb-4">Quick Links</h3>
            <ul class="space-y-2">
              <li>
                <a
                  href="#"
                  class="text-gray-400 hover:text-white transition-colors"
                  >About Us</a
                >
              </li>
              <li>
                <a
                  href="#"
                  class="text-gray-400 hover:text-white transition-colors"
                  >Contact</a
                >
              </li>
              <li>
                <a
                  href="#"
                  class="text-gray-400 hover:text-white transition-colors"
                  >FAQs</a
                >
              </li>
              <li>
                <a
                  href="#"
                  class="text-gray-400 hover:text-white transition-colors"
                  >Shipping Info</a
                >
              </li>
            </ul>
          </div>

          <div>
            <h3 class="text-lg font-medium mb-4">Follow Us</h3>
            <div class="flex space-x-4">
              <a
                href="#"
                class="w-10 h-10 flex items-center justify-center rounded-full bg-white/10 hover:bg-white/20 transition-colors"
              >
                <i class="ri-instagram-line"></i>
              </a>
              <a
                href="#"
                class="w-10 h-10 flex items-center justify-center rounded-full bg-white/10 hover:bg-white/20 transition-colors"
              >
                <i class="ri-facebook-line"></i>
              </a>
              <a
                href="#"
                class="w-10 h-10 flex items-center justify-center rounded-full bg-white/10 hover:bg-white/20 transition-colors"
              >
                <i class="ri-twitter-line"></i>
              </a>
            </div>
          </div>

          <div>
            <h3 class="text-lg font-medium mb-4">Payment Methods</h3>
            <div class="flex space-x-4">
              <i class="ri-visa-fill text-2xl"></i>
              <i class="ri-mastercard-fill text-2xl"></i>
              <i class="ri-paypal-fill text-2xl"></i>
              <i class="ri-alipay-fill text-2xl"></i>
            </div>
          </div>
        </div>

        <div
          class="border-t border-gray-800 mt-16 pt-8 text-center text-gray-400"
        >
          <p>&copy; 2025 logo. All rights reserved.</p>
        </div>
      </div>
    </footer>

    <script>
      document.addEventListener("DOMContentLoaded", function () {
        const searchInput = document.querySelector('input[type="text"]');
        const emailInput = document.querySelector('input[type="email"]');
        const subscribeForm = document.querySelector("form");

        subscribeForm.addEventListener("submit", function (e) {
          e.preventDefault();
          if (emailInput.value) {
            const toast = document.createElement("div");
            toast.className =
              "fixed bottom-4 right-4 bg-green-500 text-white px-6 py-3 rounded-lg shadow-lg transform transition-transform duration-300 translate-y-0";
            toast.textContent = "Thank you for subscribing!";
            document.body.appendChild(toast);

            setTimeout(() => {
              toast.style.transform = "translateY(200%)";
              setTimeout(() => toast.remove(), 300);
            }, 3000);

            emailInput.value = "";
          }
        });

        const addToCartButtons = document.querySelectorAll("button");
        addToCartButtons.forEach((button) => {
          if (button.textContent === "Add to Cart") {
            button.addEventListener("click", function () {
              const toast = document.createElement("div");
              toast.className =
                "fixed bottom-4 right-4 bg-primary text-white px-6 py-3 rounded-lg shadow-lg transform transition-transform duration-300 translate-y-0";
              toast.textContent = "Product added to cart!";
              document.body.appendChild(toast);

              setTimeout(() => {
                toast.style.transform = "translateY(200%)";
                setTimeout(() => toast.remove(), 300);
              }, 3000);
            });
          }
        });
      });
    </script>
  </body>
</html>
