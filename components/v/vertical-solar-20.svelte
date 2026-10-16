<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g_nt8zixb.css';
import '../../css/r/r77s4pbmz.css';
import '../../css/p/pycxazbfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="g_nt8zixb"/><path class="r77s4pbmz"/><path class="pycxazbfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:vertical-solar-20" {...props}></Icon>
