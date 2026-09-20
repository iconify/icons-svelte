<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nzxq2obzj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nzxq2obzj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:timetable" {...props}></Icon>
