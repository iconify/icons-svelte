<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ni0dax4td.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="ni0dax4td"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:signal-medium" {...props}></Icon>
