<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ysbo-7bpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ysbo-7bpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:task-user" {...props}></Icon>
