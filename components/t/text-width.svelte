<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w8alhibkb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="w8alhibkb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:text-width" {...props}></Icon>
