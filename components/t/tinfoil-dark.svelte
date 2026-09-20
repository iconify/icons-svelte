<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w10xf1pso.css';
import '../../css/m/mw546i83n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w10xf1pso"/><path class="mw546i83n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tinfoil-dark" {...props}></Icon>
