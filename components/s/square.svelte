<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xas4q0rmh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<rect class="xas4q0rmh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="charm:square" {...props}></Icon>
