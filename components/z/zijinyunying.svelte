<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwvp95byt.css';
import '../../css/p/p5rsn9lsf.css';
import '../../css/g/gtioo54ca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="wwvp95byt"><path class="p5rsn9lsf"/><path class="gtioo54ca"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:zijinyunying" {...props}></Icon>
