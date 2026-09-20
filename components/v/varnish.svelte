<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ry9ol6lsh.css';
import '../../css/o/okcsfevjn.css';
import '../../css/w/wntb9b47b.css';
import '../../css/l/ld9cusbiy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="ry9ol6lsh"><circle class="okcsfevjn"/><circle class="wntb9b47b"/><circle class="ld9cusbiy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:varnish" {...props}></Icon>
