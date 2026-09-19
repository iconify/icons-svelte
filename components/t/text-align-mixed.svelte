<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/judw4ebii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="judw4ebii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:text-align-mixed" {...props}></Icon>
