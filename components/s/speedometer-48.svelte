<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_r7mhbff.css';
import '../../css/n/nrcinobha.css';
import '../../css/r/rvdcy0bsg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="i_r7mhbff"/><path class="nrcinobha"/><path class="rvdcy0bsg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:speedometer-48" {...props}></Icon>
