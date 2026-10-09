<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r0-az_5wc.css';
import '../../css/w/wwjl5kbxm.css';
import '../../css/c/c4-hwm4yw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="r0-az_5wc"/><path class="wwjl5kbxm"/><path class="c4-hwm4yw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sensor-48-bold" {...props}></Icon>
