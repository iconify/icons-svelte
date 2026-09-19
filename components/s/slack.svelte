<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-o3bkbhj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i-o3bkbhj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:slack" {...props}></Icon>
