<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t5m82iwwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="t5m82iwwz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:text-leading" {...props}></Icon>
