<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yqlzzl8-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="yqlzzl8-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:watch-circle-charging-remix" {...props}></Icon>
