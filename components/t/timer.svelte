<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wftzxc0om.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wftzxc0om"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:timer" {...props}></Icon>
