<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vyyqn4wxr.css';
import '../../css/y/yuqpybceb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<rect class="vyyqn4wxr"/><path class="yuqpybceb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:shape-trim-filled" {...props}></Icon>
