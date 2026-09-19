<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fc3tac-mr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="fc3tac-mr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:square-caret-up" {...props}></Icon>
