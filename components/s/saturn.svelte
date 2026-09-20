<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e8l9c_b0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e8l9c_b0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:saturn" {...props}></Icon>
