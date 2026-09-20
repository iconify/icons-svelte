<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x5_pvnbbf.css';
import '../../css/w/wgglyuewc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x5_pvnbbf"/><path class="wgglyuewc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:zoom-2025-light" {...props}></Icon>
