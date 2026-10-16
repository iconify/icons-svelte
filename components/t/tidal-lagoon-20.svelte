<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mikvgmbwr.css';
import '../../css/x/x2fx8vb2p.css';
import '../../css/e/e5rhf-ewl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mikvgmbwr"/><path class="x2fx8vb2p"/><path class="e5rhf-ewl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tidal-lagoon-20" {...props}></Icon>
