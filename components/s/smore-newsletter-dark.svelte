<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wcuu03o1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wcuu03o1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:smore-newsletter-dark" {...props}></Icon>
