<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dwwxpfbew.css';
import '../../css/q/q352u0pff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="dwwxpfbew"/><path class="q352u0pff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:task-star" {...props}></Icon>
