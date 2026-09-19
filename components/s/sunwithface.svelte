<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/guaobubus.css';
import '../../css/i/i4xsl43pg.css';
import '../../css/y/y0aa2db-h.css';
import '../../css/q/q811zrblc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="guaobubus"/><circle class="i4xsl43pg"/><path class="y0aa2db-h"/><path class="q811zrblc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:sunwithface" {...props}></Icon>
