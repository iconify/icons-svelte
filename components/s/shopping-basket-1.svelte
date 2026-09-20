<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rtz05xbsa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rtz05xbsa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:shopping-basket-1" {...props}></Icon>
