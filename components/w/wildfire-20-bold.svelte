<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lyix3hqdx.css';
import '../../css/f/fqywsjpmm.css';
import '../../css/s/sv88clbwm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lyix3hqdx"/><path class="fqywsjpmm"/><path class="sv88clbwm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wildfire-20-bold" {...props}></Icon>
