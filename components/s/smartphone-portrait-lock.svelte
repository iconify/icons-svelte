<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ke6k-nk_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":304,"height":480};
const content = `<path class="ke6k-nk_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:smartphone-portrait-lock" {...props}></Icon>
