<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y83-mxdaj.css';
import '../../css/m/mdqiz-ben.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":117.173,"height":117.173};
const content = `<g transform="translate(-39.688 -207.42)"><circle class="y83-mxdaj"/><path class="mdqiz-ben"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:shiori" {...props}></Icon>
