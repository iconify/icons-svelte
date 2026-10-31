<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dedt5kbth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dedt5kbth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:scissors-round" {...props}></Icon>
