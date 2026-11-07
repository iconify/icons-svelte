<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/i/iaha13btl.css';
import '../../css/z/zhaqmra8c.css';
import '../../css/b/bi65t-brz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="iaha13btl"/><path class="zhaqmra8c"/><path class="bi65t-brz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:turntable-line-duotone" {...props}></Icon>
