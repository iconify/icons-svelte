<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/v/vkcj4bcdm.css';
import '../../css/j/j2oo8d02j.css';
import '../../css/x/xw-fp8bma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="vkcj4bcdm"/><path class="j2oo8d02j"/><path class="xw-fp8bma"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:tennis" {...props}></Icon>
