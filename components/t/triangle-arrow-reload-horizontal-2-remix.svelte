<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x68a3zbvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="x68a3zbvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:triangle-arrow-reload-horizontal-2-remix" {...props}></Icon>
