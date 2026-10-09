<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/if62vfbxx.css';
import '../../css/p/plv6-ib2c.css';
import '../../css/q/qmu5z8fin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="if62vfbxx"/><path class="plv6-ib2c"/><path class="qmu5z8fin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:solar-tile-48-bold" {...props}></Icon>
