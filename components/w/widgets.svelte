<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h4cg4-ctc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":416,"height":416};
const content = `<path class="h4cg4-ctc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:widgets" {...props}></Icon>
