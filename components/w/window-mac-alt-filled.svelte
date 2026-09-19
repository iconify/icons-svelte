<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j90bwrx1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j90bwrx1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:window-mac-alt-filled" {...props}></Icon>
