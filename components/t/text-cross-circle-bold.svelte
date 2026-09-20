<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lr3bpp98z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lr3bpp98z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:text-cross-circle-bold" {...props}></Icon>
