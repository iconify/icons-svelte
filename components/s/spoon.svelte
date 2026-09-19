<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/m/mnh5f9zfq.css';
import '../../css/o/ocruyxbsi.css';
import '../../css/h/hpyym12cz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><rect class="mnh5f9zfq"/><path class="ocruyxbsi"/><rect class="hpyym12cz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:spoon" {...props}></Icon>
