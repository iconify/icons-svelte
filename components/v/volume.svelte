<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rs9gu7n4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rs9gu7n4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:volume" {...props}></Icon>
