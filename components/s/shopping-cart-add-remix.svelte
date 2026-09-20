<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipmir7btz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ipmir7btz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:shopping-cart-add-remix" {...props}></Icon>
