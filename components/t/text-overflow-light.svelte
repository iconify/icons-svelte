<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/npcmtub9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="npcmtub9k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:text-overflow-light" {...props}></Icon>
