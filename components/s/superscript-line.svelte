<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g3wonsunq.css';
import '../../css/u/u7vxgcbwc.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 g3wonsunq"/><path class="clr-i-outline clr-i-outline-path-2 u7vxgcbwc"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:superscript-line" {...props}></Icon>
