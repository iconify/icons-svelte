<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-ohmbl_e.css';
import '../../css/m/mhdsebbpt.css';
import '../../css/i/ib5meve9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="o-ohmbl_e"/><path class="mhdsebbpt"/><path class="ib5meve9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:solar-street-light-48" {...props}></Icon>
