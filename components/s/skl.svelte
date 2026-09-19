<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rjj1zg-jm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rjj1zg-jm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:skl" {...props}></Icon>
