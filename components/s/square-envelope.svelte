<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i1mu0_w5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="i1mu0_w5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:square-envelope" {...props}></Icon>
