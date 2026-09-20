<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yiwhzubiy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="yiwhzubiy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:track-select-right-tool" {...props}></Icon>
