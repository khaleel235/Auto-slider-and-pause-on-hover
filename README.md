# Auto-slider-and-pause-on-hover
Slider for profiles, items, cards etc., It can pause or stop when we hover on card
#class is triggered by parent slider

<style>
.featured-wrapper{
  animation: moveSlideshow 15s linear infinite;
}

.featured-wrapper:hover {
    animation-play-state: paused;
  }

@keyframes moveSlideshow {
  100% { 
    transform: translateX(-30%) rotate(-2.94deg);
     transform: loop;
  }
}
</style>
