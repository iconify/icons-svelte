<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b2u8at1_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b2u8at1_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:terminal-rectangle-1-filled" {...props}></Icon>
