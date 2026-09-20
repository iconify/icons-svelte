<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pc3vo21sg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="pc3vo21sg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:search-history-browser-remix" {...props}></Icon>
