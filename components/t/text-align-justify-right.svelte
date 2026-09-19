<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dhdnz2bmj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dhdnz2bmj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:text-align-justify-right" {...props}></Icon>
