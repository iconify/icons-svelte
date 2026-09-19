<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qjri3z5pl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="qjri3z5pl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:vial-circle-check" {...props}></Icon>
