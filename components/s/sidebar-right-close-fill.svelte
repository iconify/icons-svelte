<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x2dixy0jy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x2dixy0jy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:sidebar-right-close-fill" {...props}></Icon>
