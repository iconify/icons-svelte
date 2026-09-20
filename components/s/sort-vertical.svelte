<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xenep4tzn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xenep4tzn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:sort-vertical" {...props}></Icon>
