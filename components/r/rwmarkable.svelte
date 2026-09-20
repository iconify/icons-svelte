<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xd-si8bfj.css';
import '../../css/z/zn8lzqb4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xd-si8bfj"/><path class="zn8lzqb4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rwmarkable" {...props}></Icon>
