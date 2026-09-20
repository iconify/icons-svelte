<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vjvf8qbrh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vjvf8qbrh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:snow-line" {...props}></Icon>
