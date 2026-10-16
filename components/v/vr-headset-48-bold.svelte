<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qht0pcczn.css';
import '../../css/m/mt2dtwjzm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qht0pcczn"/><path class="mt2dtwjzm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:vr-headset-48-bold" {...props}></Icon>
