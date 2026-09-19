<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r4jnmdp6q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":512};
const content = `<path class="r4jnmdp6q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:thermometer-full" {...props}></Icon>
