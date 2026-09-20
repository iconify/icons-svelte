<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mlk5hvfth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mlk5hvfth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:trademark-line" {...props}></Icon>
