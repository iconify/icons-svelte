<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c796d29xi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c796d29xi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:shop-sale-1" {...props}></Icon>
