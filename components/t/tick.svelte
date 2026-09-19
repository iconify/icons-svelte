<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<polyline points="2.75 8.75 6.25 12.25 13.25 4.75" class="hntgybcog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="charm:tick" {...props}></Icon>
