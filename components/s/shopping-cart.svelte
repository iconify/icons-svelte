<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xzhegfb8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xzhegfb8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:shopping-cart" {...props}></Icon>
