<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/srcf7abwa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="srcf7abwa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:sort-alpha-up" {...props}></Icon>
