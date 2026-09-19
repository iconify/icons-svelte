<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/g/g92amxlfl.css';
import '../../css/x/xnz_gs-_g.css';
import '../../css/j/jdh9hhorp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="g92amxlfl"/><path class="xnz_gs-_g"/><path class="jdh9hhorp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:watch" {...props}></Icon>
