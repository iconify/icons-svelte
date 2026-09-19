<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ren2jybrj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ren2jybrj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:temp-sensor" {...props}></Icon>
