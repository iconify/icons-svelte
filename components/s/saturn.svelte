<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dgj_d1b6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dgj_d1b6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:saturn" {...props}></Icon>
