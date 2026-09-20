<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/onwn_7qqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="onwn_7qqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:television-shimmer" {...props}></Icon>
