<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gjxc_mbte.css';
import '../../css/k/kymntsbrh.css';
import '../../css/u/ua5y2ubth.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 gjxc_mbte"/><path class="clr-i-outline clr-i-outline-path-2 kymntsbrh"/><path class="clr-i-outline clr-i-outline-path-3 ua5y2ubth"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:sort-by-line" {...props}></Icon>
