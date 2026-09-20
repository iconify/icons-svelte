<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hp-yh0bkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":25};
const content = `<path class="hp-yh0bkr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:shift-left" {...props}></Icon>
