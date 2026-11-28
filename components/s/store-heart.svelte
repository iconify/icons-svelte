<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/co_rkzb8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="co_rkzb8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:store-heart" {...props}></Icon>
