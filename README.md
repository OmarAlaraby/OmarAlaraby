<style>
@keyframes myAnimation {
  0% { opacity: 0; }
  100% { opacity: 1; }
}

.animation-element {
  animation-name: myAnimation;
  animation-duration: 2s;
  animation-fill-mode: forwards;
}
</style>

<div class="animation-element">This element will be animated.</div>
