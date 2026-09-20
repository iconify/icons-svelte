<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/umwb1rbmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="umwb1rbmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:stopwatch-play-outline" {...props}></Icon>
