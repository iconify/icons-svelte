<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hkk820mfz.css';
import '../../css/w/w2_kf1b2m.css';
import '../../css/x/x7_wgibau.css';
import '../../css/s/snwblib0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hkk820mfz"/><path class="w2_kf1b2m"/><path class="x7_wgibau"/><path class="snwblib0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:taxi-48" {...props}></Icon>
