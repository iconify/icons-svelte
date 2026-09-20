<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qb_9esbok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qb_9esbok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:sparkling-2-line" {...props}></Icon>
