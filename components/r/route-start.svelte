<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhhyhd2ni.css';
import '../../css/r/rug5b1b1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="yhhyhd2ni"/><path class="rug5b1b1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:route-start" {...props}></Icon>
