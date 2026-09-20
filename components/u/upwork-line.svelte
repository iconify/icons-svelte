<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rjm_bibby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rjm_bibby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:upwork-line" {...props}></Icon>
