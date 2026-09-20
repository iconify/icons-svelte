<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ruey_6b6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ruey_6b6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:slider-h-range" {...props}></Icon>
