<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w5ia4bbks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="w5ia4bbks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:text-flow-rows" {...props}></Icon>
