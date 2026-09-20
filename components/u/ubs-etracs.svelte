<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y0d4p95pm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1411,"height":1557};
const content = `<path class="y0d4p95pm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:ubs-etracs" {...props}></Icon>
