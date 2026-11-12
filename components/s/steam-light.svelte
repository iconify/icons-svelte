<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/euhhj_9fy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="euhhj_9fy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:steam-light" {...props}></Icon>
