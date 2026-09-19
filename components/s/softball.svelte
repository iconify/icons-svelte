<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y3dpzbtra.css';
import '../../css/w/w1xy-_b1v.css';
import '../../css/w/wg57ytibm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="y3dpzbtra"><path class="w1xy-_b1v"/><path class="wg57ytibm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:softball" {...props}></Icon>
