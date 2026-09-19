<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vkah-u8kr.css';
import '../../css/t/tfesq9c8z.css';
import '../../css/d/dvicfhbcp.css';
import '../../css/x/xf2_bdbsi.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<circle class="clr-i-solid clr-i-solid-path-1 vkah-u8kr"/><path class="clr-i-solid clr-i-solid-path-2 tfesq9c8z"/><path class="clr-i-solid clr-i-solid-path-3 dvicfhbcp"/><path class="clr-i-solid clr-i-solid-path-4 xf2_bdbsi"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:wifi-solid" {...props}></Icon>
