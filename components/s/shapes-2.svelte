<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zoa3gfyyl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zoa3gfyyl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:shapes-2" {...props}></Icon>
