<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xsyhy6zme.css';
import '../../css/a/ag85robiu.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 xsyhy6zme"/><path class="ag85robiu clr-i-outline clr-i-outline-path-2"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:shield-check-line" {...props}></Icon>
