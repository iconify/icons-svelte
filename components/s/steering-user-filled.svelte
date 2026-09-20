<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a2dxeqb0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a2dxeqb0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:steering-user-filled" {...props}></Icon>
