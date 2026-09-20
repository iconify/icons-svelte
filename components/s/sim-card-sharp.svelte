<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i2d0c_bnz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:sim-card-sharp" {...props}></Icon>
<style>
:global(.i2d0c_bnz) {
  fill: currentColor;
  d: path("M7.5 18.616h1v-1.424h-1zm0-3.808h1v-3.423h-1zm4 3.808h1v-3.424h-1zm0-5.808h1v-1.423h-1zm4 5.808h1v-1.424h-1zm0-3.808h1v-3.423h-1zM5 21V8.423L10.423 3H19v18z");
}

</style>
