<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pu6g42ace.css';
import '../../css/y/yo2ospfox.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid clr-i-solid-path-1 pu6g42ace"/><path class="clr-i-solid clr-i-solid-path-2 yo2ospfox"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:talk-bubbles-solid" {...props}></Icon>
