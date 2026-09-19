<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eryjosv9l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eryjosv9l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:sword-03" {...props}></Icon>
