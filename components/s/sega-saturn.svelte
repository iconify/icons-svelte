<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mk9i22bqm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mk9i22bqm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:sega-saturn" {...props}></Icon>
