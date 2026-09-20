<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o4fzgdc_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o4fzgdc_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:slider-vertical" {...props}></Icon>
