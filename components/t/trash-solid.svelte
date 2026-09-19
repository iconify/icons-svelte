<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xb258dcmc.css';
import '../../css/s/skpfrp00k.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid clr-i-solid-path-1 xb258dcmc"/><path class="clr-i-solid clr-i-solid-path-2 skpfrp00k"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:trash-solid" {...props}></Icon>
