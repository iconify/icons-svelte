<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a76k91d3g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a76k91d3g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:unfold-less-horizontal-bulk-round" {...props}></Icon>
