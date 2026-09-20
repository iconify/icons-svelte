<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/og6b60d7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="og6b60d7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:windows11" {...props}></Icon>
