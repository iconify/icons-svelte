<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wg9j96obh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wg9j96obh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:wheel-bold" {...props}></Icon>
