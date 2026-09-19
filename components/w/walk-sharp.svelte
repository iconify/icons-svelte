<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/myubtaccl.css';
import '../../css/w/wzrscbbrd.css';
import '../../css/s/sz77vjbtt.css';
import '../../css/w/wgc76mb2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="myubtaccl"/><path class="wzrscbbrd"/><path class="sz77vjbtt"/><circle class="wgc76mb2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:walk-sharp" {...props}></Icon>
