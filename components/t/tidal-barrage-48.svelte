<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ovsz64b4d.css';
import '../../css/x/x46njsebn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ovsz64b4d"/><path class="x46njsebn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tidal-barrage-48" {...props}></Icon>
