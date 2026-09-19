<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-jxcu6vs.css';
import '../../css/x/xq-7sgbpo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="i-jxcu6vs"/><path class="xq-7sgbpo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:text-highlight" {...props}></Icon>
