<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zj7a55boz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zj7a55boz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:tooltip-text" {...props}></Icon>
