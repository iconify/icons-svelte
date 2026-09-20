<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lqnmd1o0k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lqnmd1o0k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:tv-2-filled" {...props}></Icon>
