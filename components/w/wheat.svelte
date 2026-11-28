<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zgv_cbb9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zgv_cbb9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:wheat" {...props}></Icon>
