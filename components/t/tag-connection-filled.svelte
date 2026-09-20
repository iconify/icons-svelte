<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jsztftb1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="jsztftb1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:tag-connection-filled" {...props}></Icon>
