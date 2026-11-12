<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gj35uabzq.css';
import '../../css/s/sj53jabxf.css';
import '../../css/p/ptnzl-b1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gj35uabzq"/><path class="sj53jabxf"/><path class="ptnzl-b1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:windows-terminal-dark" {...props}></Icon>
