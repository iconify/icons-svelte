<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wt-fbebxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wt-fbebxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:unlink-duotone" {...props}></Icon>
