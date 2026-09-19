<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fu_owfbwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="fu_owfbwy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:user-check" {...props}></Icon>
