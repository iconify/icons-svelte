<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xbvjn4b1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="xbvjn4b1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:truck-pickup" {...props}></Icon>
