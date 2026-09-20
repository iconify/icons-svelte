<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxs996u1a.css';
import '../../css/w/wyay58blh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qxs996u1a"/><path class="wyay58blh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:spacex" {...props}></Icon>
