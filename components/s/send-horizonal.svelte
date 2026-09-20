<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r5a7x8bkn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r5a7x8bkn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:send-horizonal" {...props}></Icon>
