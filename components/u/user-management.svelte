<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yu8c7vezn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yu8c7vezn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:user-management" {...props}></Icon>
