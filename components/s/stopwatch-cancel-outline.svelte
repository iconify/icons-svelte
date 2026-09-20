<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cpb4fc6gq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cpb4fc6gq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:stopwatch-cancel-outline" {...props}></Icon>
