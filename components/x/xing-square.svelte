<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u9y9_htha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="u9y9_htha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:xing-square" {...props}></Icon>
