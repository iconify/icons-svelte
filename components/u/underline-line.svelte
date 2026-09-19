<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sd5mx2bxw.css';
import '../../css/f/ffx80zbns.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 sd5mx2bxw"/><path class="clr-i-outline clr-i-outline-path-2 ffx80zbns"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:underline-line" {...props}></Icon>
