<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ly3yfk2vt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="ly3yfk2vt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:tablet-button" {...props}></Icon>
