<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xooecg6hp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xooecg6hp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:third-stage" {...props}></Icon>
