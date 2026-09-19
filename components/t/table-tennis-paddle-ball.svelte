<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d8455lb4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d8455lb4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:table-tennis-paddle-ball" {...props}></Icon>
