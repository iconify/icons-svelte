<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jppv-o5ye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="jppv-o5ye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:ticket" {...props}></Icon>
