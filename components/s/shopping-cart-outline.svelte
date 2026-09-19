<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c6nx8fehg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="c6nx8fehg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:shopping-cart-outline" {...props}></Icon>
