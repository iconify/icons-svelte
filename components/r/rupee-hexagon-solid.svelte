<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u0vjkt74b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u0vjkt74b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:rupee-hexagon-solid" {...props}></Icon>
