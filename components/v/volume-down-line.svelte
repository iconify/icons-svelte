<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vuc8vt4xo.css';
import '../../css/r/rd91urb1p.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 vuc8vt4xo"/><path class="clr-i-outline clr-i-outline-path-2 rd91urb1p"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:volume-down-line" {...props}></Icon>
