<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ow6pd-bft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ow6pd-bft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:whiteboard-filled" {...props}></Icon>
