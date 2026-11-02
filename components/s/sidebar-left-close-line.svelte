<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tfu8o6blj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tfu8o6blj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:sidebar-left-close-line" {...props}></Icon>
