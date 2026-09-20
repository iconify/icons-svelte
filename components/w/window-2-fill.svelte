<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j29p-3uzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j29p-3uzg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:window-2-fill" {...props}></Icon>
