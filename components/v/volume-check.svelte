<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tz8on2utd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tz8on2utd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:volume-check" {...props}></Icon>
