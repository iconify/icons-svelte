<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/r/r5fs5gbsr.css';
import '../../css/c/cjkvecb0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><rect transform="rotate(45 24.762 3.243)" class="r5fs5gbsr"/><path class="cjkvecb0a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:tray" {...props}></Icon>
