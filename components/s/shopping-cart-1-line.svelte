<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q4u3a-rak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q4u3a-rak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:shopping-cart-1-line" {...props}></Icon>
