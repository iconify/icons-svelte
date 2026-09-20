<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fpc9mhzvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="fpc9mhzvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:shopping-cart-add-remix" {...props}></Icon>
