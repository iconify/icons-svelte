<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mtb0g6klh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mtb0g6klh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:windows" {...props}></Icon>
