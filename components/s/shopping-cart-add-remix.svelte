<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x8kbu62ly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x8kbu62ly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:shopping-cart-add-remix" {...props}></Icon>
