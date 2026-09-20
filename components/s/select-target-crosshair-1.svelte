<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bs9ntgcgn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bs9ntgcgn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:select-target-crosshair-1" {...props}></Icon>
