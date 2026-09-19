<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sjrzm9bfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sjrzm9bfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:worm" {...props}></Icon>
