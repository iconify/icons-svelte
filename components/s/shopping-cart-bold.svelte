<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/moy9m_k7d.css';
import '../../css/g/glv0eejpa.css';
import '../../css/u/uo28wmy_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="moy9m_k7d"/><path class="glv0eejpa"/><path class="uo28wmy_e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:shopping-cart-bold" {...props}></Icon>
