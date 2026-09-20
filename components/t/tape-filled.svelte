<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ip199ph9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ip199ph9k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:tape-filled" {...props}></Icon>
