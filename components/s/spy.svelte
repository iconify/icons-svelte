<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rfhjt5i0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rfhjt5i0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:spy" {...props}></Icon>
