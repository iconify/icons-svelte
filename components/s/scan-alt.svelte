<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8oo7gb6g.css';
import '../../css/t/tyorz8b1c.css';
import '../../css/h/htrjajb8j.css';
import '../../css/y/yqr712bef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<g class="n8oo7gb6g"><path class="tyorz8b1c"/><path class="htrjajb8j"/><path class="yqr712bef"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="marketeq:scan-alt" {...props}></Icon>
