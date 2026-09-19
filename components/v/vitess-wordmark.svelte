<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wyvahab2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="wyvahab2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:vitess-wordmark" {...props}></Icon>
