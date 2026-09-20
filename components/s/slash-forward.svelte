<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cnol5tb1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="cnol5tb1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:slash-forward" {...props}></Icon>
