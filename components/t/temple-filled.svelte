<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fujky4qvg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fujky4qvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:temple-filled" {...props}></Icon>
