<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/b/blh93uisk.css';
import '../../css/u/uue-ojz7g.css';
import '../../css/n/nv3r1zbmr.css';
import '../../css/w/wzga5cc5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="blh93uisk"/><path class="uue-ojz7g"/><circle class="nv3r1zbmr"/><circle class="wzga5cc5k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:shopping-cart-minus" {...props}></Icon>
