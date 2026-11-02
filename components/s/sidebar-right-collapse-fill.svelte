<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-bor7bpy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f-bor7bpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:sidebar-right-collapse-fill" {...props}></Icon>
