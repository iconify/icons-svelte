<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ceh-mrbpm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ceh-mrbpm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:stopwatch-subtract" {...props}></Icon>
