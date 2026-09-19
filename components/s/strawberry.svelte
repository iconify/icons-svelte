<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nnsqrrbig.css';
import '../../css/f/f-af1wzga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="nnsqrrbig"/><path class="f-af1wzga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:strawberry" {...props}></Icon>
