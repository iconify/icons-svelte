<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eelxote3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="eelxote3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:wind-flow-1-remix" {...props}></Icon>
