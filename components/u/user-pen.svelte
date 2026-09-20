<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qagtj4d3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="qagtj4d3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:user-pen" {...props}></Icon>
