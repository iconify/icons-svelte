<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/youi4hq0s.css';
import '../../css/d/d_h7705bc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="youi4hq0s"/><path class="d_h7705bc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:snow-heavy" {...props}></Icon>
