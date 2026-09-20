<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d17xp8bqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d17xp8bqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:signal-lte" {...props}></Icon>
