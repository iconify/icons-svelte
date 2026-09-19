<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uiw4tobef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1344,"height":1664};
const content = `<path class="uiw4tobef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:yahoo" {...props}></Icon>
