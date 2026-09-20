<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gyy_pbcwl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gyy_pbcwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:task-fill" {...props}></Icon>
