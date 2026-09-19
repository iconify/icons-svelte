<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="hntgybcog"><polyline points="10.25 2.75 2.75 2.75 2.75 13.25 13.25 13.25 13.25 9.75"/><polyline points="5.75 7.75 8.25 10.25 14.25 3.75"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="charm:square-tick" {...props}></Icon>
