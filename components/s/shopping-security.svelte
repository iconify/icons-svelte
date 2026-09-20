<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/npc39g6la.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="npc39g6la"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:shopping-security" {...props}></Icon>
