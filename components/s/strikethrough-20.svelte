<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ctlj9gncl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ctlj9gncl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:strikethrough-20" {...props}></Icon>
