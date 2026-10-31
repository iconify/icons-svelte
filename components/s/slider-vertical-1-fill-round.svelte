<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yahzeibjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yahzeibjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:slider-vertical-1-fill-round" {...props}></Icon>
