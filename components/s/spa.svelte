<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mvem3hemn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":662};
const content = `<path class="mvem3hemn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:spa" {...props}></Icon>
