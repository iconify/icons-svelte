<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rgdyellrq.css';
import '../../css/s/slqdrx-ov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rgdyellrq"/><path class="slqdrx-ov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:sleeping-bold" {...props}></Icon>
