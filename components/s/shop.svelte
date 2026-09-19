<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/p/prvg-xbay.css';
import '../../css/x/x0yq8fapu.css';
import '../../css/n/ny1ve4bvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="prvg-xbay"/><path class="x0yq8fapu"/><path class="ny1ve4bvd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:shop" {...props}></Icon>
