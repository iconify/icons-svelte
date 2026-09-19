<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9ga4kbog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="y9ga4kbog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:two" {...props}></Icon>
