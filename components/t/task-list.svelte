<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-bko7bcx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="u-bko7bcx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:task-list" {...props}></Icon>
