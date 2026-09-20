<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ez9oioo_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ez9oioo_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:tram" {...props}></Icon>
