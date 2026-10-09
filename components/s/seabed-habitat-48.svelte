<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wfx3nk7mg.css';
import '../../css/w/wqd1m4bbm.css';
import '../../css/w/w-k7occ-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wfx3nk7mg"/><path class="wqd1m4bbm"/><path class="w-k7occ-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:seabed-habitat-48" {...props}></Icon>
