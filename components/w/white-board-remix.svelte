<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mst73-bah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="mst73-bah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:white-board-remix" {...props}></Icon>
