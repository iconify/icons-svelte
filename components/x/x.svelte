<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ga9bzj9gz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ga9bzj9gz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:x" {...props}></Icon>
