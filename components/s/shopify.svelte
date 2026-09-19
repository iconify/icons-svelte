<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bilw1i94r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="bilw1i94r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:shopify" {...props}></Icon>
