<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_8-i3bpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c_8-i3bpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:task-line" {...props}></Icon>
