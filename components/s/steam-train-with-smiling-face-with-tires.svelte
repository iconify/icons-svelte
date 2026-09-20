<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fd3rb99cx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="fd3rb99cx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:steam-train-with-smiling-face-with-tires" {...props}></Icon>
