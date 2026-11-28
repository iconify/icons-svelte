<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rkdltbczp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rkdltbczp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:star-minus" {...props}></Icon>
