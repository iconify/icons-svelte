<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xylo4ccpg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xylo4ccpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:search-ai-fill" {...props}></Icon>
