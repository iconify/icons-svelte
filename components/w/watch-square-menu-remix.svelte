<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s93-4-ktg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="s93-4-ktg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:watch-square-menu-remix" {...props}></Icon>
