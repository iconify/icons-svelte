<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dhoz0_dzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dhoz0_dzf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:upload-menu" {...props}></Icon>
