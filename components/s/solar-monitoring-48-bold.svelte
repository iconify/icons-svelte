<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/om_2m0e4d.css';
import '../../css/z/zhkqvsbwg.css';
import '../../css/a/axb1k_ble.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="om_2m0e4d"/><path class="zhkqvsbwg"/><path class="axb1k_ble"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:solar-monitoring-48-bold" {...props}></Icon>
