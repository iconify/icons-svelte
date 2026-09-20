<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sq2-pcbaa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:villa-outline-sharp" {...props}></Icon>
<style>
:global(.sq2-pcbaa) {
  fill: currentColor;
  d: path("M3 21V8l13-5v9h1q0-.825.588-1.412T19 10t1.413.588T21 12v9zm2-2h4v-7h5V5.9L5 9.375zm6 0h3v-3h2v3h3v-5h-8zm4-.5");
}

</style>
