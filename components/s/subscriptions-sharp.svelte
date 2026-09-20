<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="go7qw9bws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:subscriptions-sharp" {...props}></Icon>
<style>
:global(.go7qw9bws) {
  fill: currentColor;
  d: path("M3 21V9h18v12zm7.5-2.923L15.116 15L10.5 11.923zm-6-10.846v-1h15v1zm3-2.77v-1h9v1z");
}

</style>
