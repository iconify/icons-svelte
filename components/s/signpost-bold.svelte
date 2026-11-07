<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jb_o3ebip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jb_o3ebip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:signpost-bold" {...props}></Icon>
