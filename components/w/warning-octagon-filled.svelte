<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bd1c23p7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bd1c23p7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:warning-octagon-filled" {...props}></Icon>
