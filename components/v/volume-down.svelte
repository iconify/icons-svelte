<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qwfgu54tm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qwfgu54tm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:volume-down" {...props}></Icon>
