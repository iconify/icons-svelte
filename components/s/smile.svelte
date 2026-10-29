<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/utqzt6bcp.css';
import '../../css/u/ubxtf-bat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="utqzt6bcp wm-k"/><path class="ubxtf-bat wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:smile" {...props}></Icon>
