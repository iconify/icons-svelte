<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mu_-hqblm.css';
import '../../css/l/lx1bjzy7s.css';
import '../../css/r/rkhp_zb5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mu_-hqblm"/><path class="lx1bjzy7s"/><path class="rkhp_zb5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:school-48" {...props}></Icon>
