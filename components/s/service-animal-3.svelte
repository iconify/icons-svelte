<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ryqn2dhuu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ryqn2dhuu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:service-animal-3" {...props}></Icon>
