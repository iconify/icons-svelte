<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w7bj30f0q.css';
import '../../css/t/thj5gk-ag.css';
import '../../css/r/rututhb5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<circle class="w7bj30f0q"/><path class="thj5gk-ag"/><path class="rututhb5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:task-location" {...props}></Icon>
