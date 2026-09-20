<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nc9lc3bdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="nc9lc3bdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:screen-2-remix" {...props}></Icon>
