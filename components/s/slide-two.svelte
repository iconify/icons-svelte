<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/r/r9ztc99mw.css';
import '../../css/z/zw37bnb8x.css';
import '../../css/m/m6j54zbzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="r9ztc99mw"/><path clip-rule="evenodd" class="zw37bnb8x"/><path class="m6j54zbzf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:slide-two" {...props}></Icon>
