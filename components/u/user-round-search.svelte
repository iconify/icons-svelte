<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yrk5zut0w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yrk5zut0w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:user-round-search" {...props}></Icon>
