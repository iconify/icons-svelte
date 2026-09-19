<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eye2jmcul.css';
import '../../css/u/uvvdcns2p.css';
import '../../css/y/ypamjenez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<g class="eye2jmcul"><path class="uvvdcns2p"/><path class="ypamjenez"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:sourcetree-wordmark" {...props}></Icon>
