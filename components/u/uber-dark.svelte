<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sp2647b5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":926.905,"height":321.777};
const content = `<path class="sp2647b5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:uber-dark" {...props}></Icon>
