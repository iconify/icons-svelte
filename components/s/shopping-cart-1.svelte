<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwvp95byt.css';
import '../../css/j/j8-bju_yg.css';
import '../../css/l/lyvu_j98b.css';
import '../../css/y/y01qu0bsu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="wwvp95byt"><path class="j8-bju_yg"/><path class="lyvu_j98b"/><path class="y01qu0bsu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:shopping-cart-1" {...props}></Icon>
