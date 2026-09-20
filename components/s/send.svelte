<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xacg5pbsc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xacg5pbsc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:send" {...props}></Icon>
