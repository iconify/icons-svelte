<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uxr668a_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uxr668a_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:usercase-filled" {...props}></Icon>
