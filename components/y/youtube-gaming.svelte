<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/thw8f5_hf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="thw8f5_hf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:youtube-gaming" {...props}></Icon>
