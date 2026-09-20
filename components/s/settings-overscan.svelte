<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c5spjmstw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:settings-overscan" {...props}></Icon>
<style>
:global(.c5spjmstw) {
  fill: currentColor;
  d: path("M6.846 13.616v-3.231L5.231 12zM12 16.769l1.616-1.615h-3.231zm-1.616-7.923h3.231L12 7.231zm6.77 4.77L18.769 12l-1.615-1.616zM4.616 19q-.691 0-1.153-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h14.77q.69 0 1.152.463T21 6.616v10.769q0 .69-.463 1.153T19.385 19z");
}

</style>
