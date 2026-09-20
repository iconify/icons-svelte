<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c2jwg7bwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="c2jwg7bwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:table-add-row-after" {...props}></Icon>
