<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lq6pfdcca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lq6pfdcca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:strikethrough-a" {...props}></Icon>
