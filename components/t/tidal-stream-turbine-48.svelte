<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pfm2ybc6q.css';
import '../../css/s/szotk6bxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pfm2ybc6q"/><path class="szotk6bxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tidal-stream-turbine-48" {...props}></Icon>
