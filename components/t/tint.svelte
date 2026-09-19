<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_lhe9xti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="b_lhe9xti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:tint" {...props}></Icon>
