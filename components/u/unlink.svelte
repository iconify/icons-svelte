<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iy71xu2ad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iy71xu2ad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codex:unlink" {...props}></Icon>
