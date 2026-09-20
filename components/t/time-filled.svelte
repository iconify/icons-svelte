<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r57lzjb4e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r57lzjb4e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:time-filled" {...props}></Icon>
