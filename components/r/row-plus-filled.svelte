<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yexni8b3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yexni8b3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:row-plus-filled" {...props}></Icon>
