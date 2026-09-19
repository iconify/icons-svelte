<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bb9qjw3fz.css';
import '../../css/y/yd1q8xhfp.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="bb9qjw3fz clr-i-outline clr-i-outline-path-1"/><path class="clr-i-outline clr-i-outline-path-2 yd1q8xhfp"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:subscript-line" {...props}></Icon>
