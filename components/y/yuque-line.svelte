<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oxk8nxb5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oxk8nxb5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:yuque-line" {...props}></Icon>
