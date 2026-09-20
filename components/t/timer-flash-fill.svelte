<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/amd_3bbix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="amd_3bbix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:timer-flash-fill" {...props}></Icon>
