<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/g/ggb7x-boh.css';
import '../../css/l/ldty1h41z.css';
import '../../css/h/h_tsn8bxt.css';
import '../../css/j/jtil8bcce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ggb7x-boh"/><path class="ldty1h41z"/><circle class="h_tsn8bxt"/><path class="jtil8bcce"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:translation-2-broken" {...props}></Icon>
