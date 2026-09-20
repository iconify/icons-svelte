<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jpkqq8beq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jpkqq8beq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:takeoff" {...props}></Icon>
