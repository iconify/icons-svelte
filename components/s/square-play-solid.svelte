<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hy6ofvbdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hy6ofvbdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:square-play-solid" {...props}></Icon>
