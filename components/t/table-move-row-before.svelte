<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d9w_to-ne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="d9w_to-ne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:table-move-row-before" {...props}></Icon>
