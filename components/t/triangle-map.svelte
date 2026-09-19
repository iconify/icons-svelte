<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cq2drpblx.css';
import '../../css/g/gi07l0tvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="cq2drpblx"/><path class="gi07l0tvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:triangle-map" {...props}></Icon>
