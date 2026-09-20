<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mupqp8cxu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="mupqp8cxu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:rounded-triangle-right-outline" {...props}></Icon>
