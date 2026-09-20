<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/auyavi8jz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="auyavi8jz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:truck-filled" {...props}></Icon>
