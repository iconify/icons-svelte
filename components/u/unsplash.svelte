<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/twp1bxbyz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="twp1bxbyz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:unsplash" {...props}></Icon>
