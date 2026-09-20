<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mfk9sbw9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mfk9sbw9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:table-move-row-after" {...props}></Icon>
