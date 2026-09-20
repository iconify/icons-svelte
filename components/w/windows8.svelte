<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/af9gyabim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="af9gyabim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:windows8" {...props}></Icon>
