<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bizb7ubav.css';
import '../../css/m/m3tp5udax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bizb7ubav"/><path class="m3tp5udax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:server-sftp-folder" {...props}></Icon>
