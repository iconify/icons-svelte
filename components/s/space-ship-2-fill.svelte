<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bjtaybc8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bjtaybc8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:space-ship-2-fill" {...props}></Icon>
