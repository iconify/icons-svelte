<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ep_t08zig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ep_t08zig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:tag-solid" {...props}></Icon>
