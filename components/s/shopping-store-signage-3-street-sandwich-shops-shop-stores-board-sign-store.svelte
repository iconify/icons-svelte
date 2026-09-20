<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gdj9-9bee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="gdj9-9bee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:shopping-store-signage-3-street-sandwich-shops-shop-stores-board-sign-store" {...props}></Icon>
