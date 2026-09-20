<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j-2k72xgs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j-2k72xgs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:synagogue" {...props}></Icon>
