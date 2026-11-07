<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/s/sb0q3diim.css';
import '../../css/s/s9qxbdczi.css';
import '../../css/r/r22-xebfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="sb0q3diim"/><path class="s9qxbdczi"/><path class="r22-xebfg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:ruler-angular-linear" {...props}></Icon>
