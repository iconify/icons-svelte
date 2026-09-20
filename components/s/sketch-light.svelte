<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r8ss29b8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="r8ss29b8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:sketch-light" {...props}></Icon>
