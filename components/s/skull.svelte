<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q0c2y_bmk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="q0c2y_bmk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:skull" {...props}></Icon>
