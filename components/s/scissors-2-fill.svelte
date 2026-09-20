<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tuz0hewbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tuz0hewbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:scissors-2-fill" {...props}></Icon>
