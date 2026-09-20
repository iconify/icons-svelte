<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xv0tkkeho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xv0tkkeho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:snapchat-fill" {...props}></Icon>
