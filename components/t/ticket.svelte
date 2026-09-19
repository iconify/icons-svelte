<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/f/fqag3lg0a.css';
import '../../css/i/ins8vbbfb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="hntgybcog"><path class="fqag3lg0a"/><path class="ins8vbbfb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="charm:ticket" {...props}></Icon>
