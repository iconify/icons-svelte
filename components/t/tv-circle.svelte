<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xjy9wnb-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="xjy9wnb-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:tv-circle" {...props}></Icon>
