<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z37mi_bfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z37mi_bfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:shopping-basket-fill" {...props}></Icon>
