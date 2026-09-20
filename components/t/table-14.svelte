<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fpi5iabqq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="fpi5iabqq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:table-14" {...props}></Icon>
