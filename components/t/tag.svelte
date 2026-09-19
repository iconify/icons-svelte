<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/l/l0_m7cbau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="hntgybcog"><polygon points="7.25 14.25 1.75 8.75 8.75 1.75 14.25 1.75 14.25 7.25"/><circle class="l0_m7cbau"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="charm:tag" {...props}></Icon>
