<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mi44fdc-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mi44fdc-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:three-stars-solid" {...props}></Icon>
