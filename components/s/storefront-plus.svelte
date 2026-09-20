<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cq7n5t20k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cq7n5t20k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:storefront-plus" {...props}></Icon>
