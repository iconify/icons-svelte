<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ccnocllyv.css';
import '../../css/e/eb4h0cb7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ccnocllyv"/><path class="eb4h0cb7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sparkline-20" {...props}></Icon>
