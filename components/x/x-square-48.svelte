<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xx2xmtbjn.css';
import '../../css/b/bay9ped7x.css';
import '../../css/x/xohk6ubyz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xx2xmtbjn"/><path class="bay9ped7x"/><path class="xohk6ubyz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:x-square-48" {...props}></Icon>
