<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fclyj503u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fclyj503u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:soap" {...props}></Icon>
