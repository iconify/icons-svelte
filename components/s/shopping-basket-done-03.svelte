<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yr_8_8m1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yr_8_8m1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:shopping-basket-done-03" {...props}></Icon>
