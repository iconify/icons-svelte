<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rxx0zybpe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":666,"height":681};
const content = `<path class="rxx0zybpe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:underline" {...props}></Icon>
