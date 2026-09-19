<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oy99ozzcb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1824,"height":1472};
const content = `<path class="oy99ozzcb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:volume-times" {...props}></Icon>
