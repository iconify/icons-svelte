<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zymrr9x_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zymrr9x_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:slider-vertical-2-round" {...props}></Icon>
