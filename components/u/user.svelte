<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ktds2lb-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ktds2lb-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:user" {...props}></Icon>
