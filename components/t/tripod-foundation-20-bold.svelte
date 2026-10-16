<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vk81lsb-f.css';
import '../../css/v/vmw5ydxzv.css';
import '../../css/t/ta92rdbgt.css';
import '../../css/q/qiqf2wm_a.css';
import '../../css/y/yfoxxnbix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vk81lsb-f"/><path class="vmw5ydxzv"/><path class="ta92rdbgt"/><path class="qiqf2wm_a"/><path class="yfoxxnbix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tripod-foundation-20-bold" {...props}></Icon>
