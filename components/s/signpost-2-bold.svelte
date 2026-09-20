<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ztn9307gx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ztn9307gx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:signpost-2-bold" {...props}></Icon>
