<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lrnnfb6_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="lrnnfb6_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:tired-face-with-sweat-in-circle-outline" {...props}></Icon>
