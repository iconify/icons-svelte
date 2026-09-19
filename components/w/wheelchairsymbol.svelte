<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o4xf1bb5l.css';
import '../../css/r/r8hexeb-r.css';
import '../../css/c/cdedgs6la.css';
import '../../css/a/a0p8v79-c.css';
import '../../css/p/pox_jy--p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o4xf1bb5l"/><path class="r8hexeb-r"/><circle class="cdedgs6la"/><path class="a0p8v79-c"/><path class="pox_jy--p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:wheelchairsymbol" {...props}></Icon>
