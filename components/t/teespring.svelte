<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uyr2k2qmg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="uyr2k2qmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:teespring" {...props}></Icon>
