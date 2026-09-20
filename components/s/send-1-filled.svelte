<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dh594qf6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dh594qf6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:send-1-filled" {...props}></Icon>
