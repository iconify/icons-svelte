<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/e/ehz7_oblv.css';
import '../../css/r/r0dhu9b3t.css';
import '../../css/h/h_tsn8bxt.css';
import '../../css/j/jtil8bcce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ehz7_oblv"/><path class="r0dhu9b3t"/><circle class="h_tsn8bxt"/><path class="jtil8bcce"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:translation-2-linear" {...props}></Icon>
