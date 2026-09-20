<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx118f5my.css';
import '../../css/b/btb61zlai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jx118f5my"/><path class="btb61zlai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:shopping-cart-1-line" {...props}></Icon>
