<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q8r_qsbws.css';
import '../../css/r/ry01m7_4o.css';
import '../../css/b/bbwelfbky.css';
import '../../css/w/w4lj5sbru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="q8r_qsbws"/><path class="ry01m7_4o"/><path class="bbwelfbky"/><path class="w4lj5sbru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:solar-canopy-48" {...props}></Icon>
