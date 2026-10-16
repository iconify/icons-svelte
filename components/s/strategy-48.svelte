<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cehi_ab5l.css';
import '../../css/l/lp3-t_bhn.css';
import '../../css/p/phjpdo02s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="cehi_ab5l"/><path class="lp3-t_bhn"/><path class="phjpdo02s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:strategy-48" {...props}></Icon>
