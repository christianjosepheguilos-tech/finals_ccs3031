
<template>
  <section class="Featured" id="featured">
    <div class="container">
      <p class="subtitle">OUR FAVORITES</p>
      <h2>Featured Products</h2>
      <p class="description">
        Discover your new favorite drink and enjoy every sip
        at Kape ni Emman.
      </p>

      <div class="products">
        <div class="product-card">
            <img src="@/assets/image/cinnamon.png" alt=" Logo" />
          <h3>Cinnamon Crisp</h3>
          <p>Sweet, crunchy, and packed with warm cinnamon flavor in every bite.</p>
          <h4>₱155</h4>
        </div>

        <div class="product-card">
          <img src="@/assets/image/matcha.png" alt=" Logo" />
          <h3>Sea Salt Matcha</h3>
          <p>Vibrant matcha meets a hint of sea salt. Smooth, energizing, and perfectly balanced.</p>
          <h4>₱155</h4>
        </div>

        <div class="product-card">
          <img src="@/assets/image/Fcoffe.png" alt=" Logo" />
          <h3>Iced Matcha Latte</h3>
          <p>Smooth espresso, rich condensed milk, and a cool splash of creaminess over ice.</p>
          <h4>₱155</h4>
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped>
.Featured {
  width: 100%;
  background-color:  #e6eadb;
  padding: 60px 20px;
  box-sizing: border-box;
}

.container {
  max-width: 1200px;
  width: 100%;
  margin: 0 auto;
  text-align: center;
}

.subtitle {
  color: rgb(73, 26, 26);
  font-weight: bold;
  font-size: 15px;
}

h2 {
  color:rgb(126, 10, 10);
  font-size: 36px;
  margin-bottom: 15px;
}

.description {
  color: #444444;
  font-size: 17px;
  margin-bottom: 35px;
}

.products {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  gap: 25px;
}

.product-card {
  width: 240px;
  max-width: 100%;
  background-color: rgb(101, 11, 11);
  border-radius: 10px;
  padding: 15px;
  
}

.product-card img {
  width: 100%;
  height: 190px;
  object-fit: cover;
  border-radius: 7px;
}

.product-card h3 {
  color: white;
  font-size: 20px;
}

.product-card p {
  color: rgb(201, 180, 180);
  font-size: 15px;
}

.product-card h4 {
  color: rgb(245, 94, 94);
  font-size: 20px;
}

@media (max-width: 600px) {
  .Featured {
    padding: 40px 15px;
  }

  h2 {
    font-size: 29px;
  }

  .products {
    gap: 15px;
  }

  .product-card {
    width: 100%;
    max-width: 320px;
  }

  .product-card img {
    height: 220px;
  }
}
</style>
