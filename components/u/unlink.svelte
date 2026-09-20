<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cc32zrb2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cc32zrb2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:unlink" {...props}></Icon>
