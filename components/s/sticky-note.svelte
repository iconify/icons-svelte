<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="hntgybcog"><polygon points="9.25 13.25 2.75 13.25 2.75 2.75 13.25 2.75 13.25 9.25"/><polyline points="8.75 13.25 8.75 8.75 13.25 8.75"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="charm:sticky-note" {...props}></Icon>
