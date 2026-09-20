<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j0g57acut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j0g57acut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:vulkan" {...props}></Icon>
