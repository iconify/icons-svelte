<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/frb1tob9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="frb1tob9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:scribd" {...props}></Icon>
