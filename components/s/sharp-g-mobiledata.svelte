<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="asosj7d7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-g-mobiledata" {...props}></Icon>
<style>
:global(.asosj7d7h) {
  fill: currentColor;
  d: path("M12 11v2h2v2H9V9h7V7H7v10h9v-6z");
}

</style>
