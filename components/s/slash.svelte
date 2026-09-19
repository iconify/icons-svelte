<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zjkq6u0-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":383,"height":854};
const content = `<path class="zjkq6u0-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:slash" {...props}></Icon>
