<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-9gbzbrv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r-9gbzbrv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:speaker-2-line" {...props}></Icon>
