<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fp02g-bms.css';
import '../../css/r/roowebboo.css';
import '../../css/r/rviy4nhfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fp02g-bms"/><path class="roowebboo"/><path class="rviy4nhfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:van-48" {...props}></Icon>
