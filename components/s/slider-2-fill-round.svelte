<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r093a8ojm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r093a8ojm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:slider-2-fill-round" {...props}></Icon>
