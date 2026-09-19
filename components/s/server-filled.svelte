<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/srh2llbzj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="srh2llbzj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:server-filled" {...props}></Icon>
