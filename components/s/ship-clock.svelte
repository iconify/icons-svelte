<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s77q7qbma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s77q7qbma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:ship-clock" {...props}></Icon>
