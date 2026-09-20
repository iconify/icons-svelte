<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_nlz8qfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f_nlz8qfy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:terminal-rectangle-filled" {...props}></Icon>
