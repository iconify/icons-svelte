<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yt7ejub1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yt7ejub1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:sort-calendar-descending" {...props}></Icon>
