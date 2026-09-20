<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jm0noqbqz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:sort-by-alpha-sharp" {...props}></Icon>
<style>
:global(.jm0noqbqz) {
  fill: currentColor;
  d: path("M2 17L5.75 7H7.9l3.75 10H9.6l-.85-2.4H4.9L4.1 17zm3.5-4.1h2.6L6.9 9.15h-.15zm8.2 4.1v-1.9l5.05-6.3H13.9V7h7.05v1.9l-5 6.3H21V17zM9 5l3-3l3 3zm3 17l-3-3h6z");
}

</style>
