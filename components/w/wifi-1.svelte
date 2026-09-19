<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-o8jnbxm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="g-o8jnbxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:wifi-1" {...props}></Icon>
