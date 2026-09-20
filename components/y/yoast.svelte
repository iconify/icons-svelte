<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9_w5jbjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="y9_w5jbjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:yoast" {...props}></Icon>
