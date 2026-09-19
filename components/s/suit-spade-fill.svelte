<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jz-0r32uk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="jz-0r32uk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:suit-spade-fill" {...props}></Icon>
