<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cx7pxbcua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cx7pxbcua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:sun-plus" {...props}></Icon>
