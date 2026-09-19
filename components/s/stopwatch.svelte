<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vbkwunbel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="vbkwunbel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:stopwatch" {...props}></Icon>
