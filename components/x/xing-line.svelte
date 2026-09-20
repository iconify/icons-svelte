<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r94-7wsro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r94-7wsro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:xing-line" {...props}></Icon>
