<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r5r94jbqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="r5r94jbqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:warehouse-1-remix" {...props}></Icon>
