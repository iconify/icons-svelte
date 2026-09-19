<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/awg3alaya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="awg3alaya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:start" {...props}></Icon>
