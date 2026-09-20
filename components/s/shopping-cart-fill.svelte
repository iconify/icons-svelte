<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bbsw-ac5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bbsw-ac5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:shopping-cart-fill" {...props}></Icon>
