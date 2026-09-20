<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u9pgkkb6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="u9pgkkb6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:undo-ltr" {...props}></Icon>
