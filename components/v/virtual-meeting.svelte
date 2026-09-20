<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qmhj1ffwj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qmhj1ffwj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:virtual-meeting" {...props}></Icon>
