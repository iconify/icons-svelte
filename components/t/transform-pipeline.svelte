<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s78iaqrgr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="s78iaqrgr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:transform-pipeline" {...props}></Icon>
