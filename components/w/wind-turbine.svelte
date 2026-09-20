<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/csi_j9bmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="csi_j9bmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:wind-turbine" {...props}></Icon>
