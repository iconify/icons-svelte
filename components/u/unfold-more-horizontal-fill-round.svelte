<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uy_rklbjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uy_rklbjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:unfold-more-horizontal-fill-round" {...props}></Icon>
