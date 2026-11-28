<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iuchlbb6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iuchlbb6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:wifi-x" {...props}></Icon>
