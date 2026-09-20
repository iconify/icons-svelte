<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":291};
const content = `<path class="rrrzphlor"/><path class="p3gpbob8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="logos:terraform-icon" {...props}></Icon>
<style>
:global(.p3gpbob8t) {
  fill: var(--svg-color--5c4ee5, #5c4ee5);
  d: path("m88.243 51.249l79.515 45.963v91.782L88.243 143.08M0 91.83l79.515 45.916v-91.83L0 0m88.243 244.994l79.515 45.915v-91.83l-79.515-45.915");
}

:global(.rrrzphlor) {
  fill: var(--svg-color--4040b2, #4040b2);
  d: path("M176.485 188.994L256 143.127V51.249l-79.515 45.963z");
}

</style>
