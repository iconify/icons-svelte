<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xefpuv2ro.css';
import '../../css/m/mtpevtoup.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid clr-i-solid-path-1 xefpuv2ro"/><path class="clr-i-solid clr-i-solid-path-2 mtpevtoup"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:tree-solid" {...props}></Icon>
