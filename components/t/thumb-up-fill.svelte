<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jo70_cbhg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jo70_cbhg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:thumb-up-fill" {...props}></Icon>
