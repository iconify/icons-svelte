<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hy-485wlr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hy-485wlr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:table-add-row-before" {...props}></Icon>
