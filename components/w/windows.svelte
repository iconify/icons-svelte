<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g4707bcna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g4707bcna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:windows" {...props}></Icon>
