<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r4c47gkwc.css';
import '../../css/r/rvgwmpbdo.css';
import '../../css/h/h-k86boip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r4c47gkwc"/><path class="rvgwmpbdo"/><path class="h-k86boip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:threebuttonmouse" {...props}></Icon>
