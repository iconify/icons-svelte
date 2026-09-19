<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3lph30dl.css';
import '../../css/m/mhwosdh5o.css';
import '../../css/x/xpua17bdp.css';
import '../../css/p/ple3qktap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="l3lph30dl"><path class="mhwosdh5o"/><rect class="xpua17bdp"/><path class="ple3qktap"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:vertically-centered" {...props}></Icon>
