<template>
  <div style="background-color: #00001a;">
    
    <div class="w3-container" style="background-color: #e6e6ff; text-align: center;">
      <h1>Header</h1>
    </div>
    
    
    <div class="w3-row">
<div class="w3-third w3-container" style="background-color: #d9b3ff; color: #1a0033;">
  <h2>Menu</h2>
  <p>The w3-twothird class uses 33% of parent container.</p>
  <p>On screens smaller than 601 pixels it resizes to full screen.</p>
</div>
<div class="w3-twothird w3-container" style="color: #f2e6ff;">
  <h2>Status</h2>  
  <p>The w3-twothird class uses 66% of the parent container.</p>
  <p>On screens smaller than 601 pixels it resizes to full screen.</p>
</div>
</div>
    
    
    <div style="background-color: blue;"> 
    <slot />
    </div>
    
  </div>
  
  <link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">

</template>