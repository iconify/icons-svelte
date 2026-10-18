<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fhz704nam.css';
import '../../css/o/odoplnlhz.css';
import '../../css/k/kv_uf3bpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fhz704nam"/><path class="odoplnlhz"/><path class="kv_uf3bpr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:solar-monitoring-20-bold" {...props}></Icon>
