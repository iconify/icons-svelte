<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vcfttybhh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vcfttybhh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:unfold-less-horizontal-duotone-round" {...props}></Icon>
