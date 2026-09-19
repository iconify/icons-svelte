<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oqxc8o3zi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="oqxc8o3zi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:window-restore" {...props}></Icon>
