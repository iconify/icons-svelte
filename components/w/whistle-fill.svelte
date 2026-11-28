<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ln38mfb1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="ln38mfb1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:whistle-fill" {...props}></Icon>
