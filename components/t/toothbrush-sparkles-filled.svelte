<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rusr7tbak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rusr7tbak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:toothbrush-sparkles-filled" {...props}></Icon>
