<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lrk2ge1sl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lrk2ge1sl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:shield-search" {...props}></Icon>
