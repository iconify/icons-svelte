<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aosvgyiyn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1664};
const content = `<g transform="translate(0 1664) scale(1 -1)"><path class="aosvgyiyn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:thumbs-o-down" {...props}></Icon>
