<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8t899j6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="h8t899j6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:skill-level-intermediate" {...props}></Icon>
