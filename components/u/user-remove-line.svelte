<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nxnxe3krn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nxnxe3krn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:user-remove-line" {...props}></Icon>
