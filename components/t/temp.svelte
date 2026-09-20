<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jhh9nsb2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jhh9nsb2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:temp" {...props}></Icon>
