<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3ytnwbhg.css';
import '../../css/o/o89w-k64d.css';
import '../../css/c/c9uy2uufm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="v3ytnwbhg"/><path class="o89w-k64d"/><path class="c9uy2uufm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:solar-tile-20-bold" {...props}></Icon>
