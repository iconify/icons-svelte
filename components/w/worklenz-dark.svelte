<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/re446-bxy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="re446-bxy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:worklenz-dark" {...props}></Icon>
