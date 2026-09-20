<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f7mhy5b_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f7mhy5b_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:tally-five-solid" {...props}></Icon>
