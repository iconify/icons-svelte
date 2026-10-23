<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z20gk7b7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z20gk7b7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:shopping-cart-minus" {...props}></Icon>
