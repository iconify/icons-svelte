<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e7vx6y1bx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e7vx6y1bx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:search-plus" {...props}></Icon>
