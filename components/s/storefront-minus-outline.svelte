<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pvdz56ifx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pvdz56ifx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:storefront-minus-outline" {...props}></Icon>
